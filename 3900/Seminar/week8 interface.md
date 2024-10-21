```dataviewjs
// 获取所有页面的任务
let tasks = dv.pages()
  .where(p => p.file.tasks) // 确保页面包含任务
  .flatMap(p => p.file.tasks) // 提取所有任务
  //.filter(t => t.text.includes(filterTag));

// 筛选未完成的任务并提取文本
let taskTexts = tasks
  .filter(t => t.completed === false) // 筛选未完成的任务
  .map(t => t.text.replace(/#.*?(\s|$)/g, '').trim()) // 去掉#及后面的内容并清理文本

// 显示任务文本列表，不显示标签
dv.list(taskTexts);
```
