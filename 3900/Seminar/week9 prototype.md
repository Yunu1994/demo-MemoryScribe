```dataviewjs
//显示任务列表，保持链接功能
// 获取所有页面的任务
let tasks = dv.pages()
  .where(p => p.file.tasks) // 确保页面包含任务
  .flatMap(p => p.file.tasks) // 提取所有任务
  .filter(t => t.text.includes("2024-9-30")); // 筛选未完成的任务
// 清理任务文本，去掉#后面的内容
tasks.forEach(t => {
  t.text = t.text.replace(/#.*?(\s|$)/g, '').trim(); // 去掉#及后面的内容
});
// 显示任务列表，保持链接功能
dv.taskList(tasks);
```