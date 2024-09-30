---

kanban-plugin: board

---

## 9.29

- [ ] ```dataview 
	task where contains(tags, "2024-9-29")
- [ ] 20:42 test2 test
- [ ] 21:07 完成 prepare kanban
- [ ] 22:08 代码 dataviewjs
	//显示任务列表
- [ ] 23 ddd
- [ ] sleep
- [ ] 22:11 test no selected text


## 9.30

- [ ] ```dataview 
	task where contains(tags, "2024-9-30")


## 10.1

- [ ] ```dataviewjs
	// 获取所有页面的任务
	let tasks = dv.pages()
	  .where(p => p.file.tasks && !p.file.path.includes("kanban")) // 确保页面包含任务
	  .flatMap(p => p.file.tasks) // 提取所有任务
	  .filter(t => t.text.includes("2024-10-1")); // 筛选未完成的任务
	// 清理任务文本，去掉#后面的内容
	tasks.forEach(t => {
	  t.text = t.text.replace(/#.*?(\s|$)/g, '').trim(); // 去掉#及后面的内容
	});
	// 显示任务列表，保持链接功能
	dv.taskList(tasks);


## 10.2

- [ ] ```dataview 
	task where contains(tags, "2024-10-2") sort file.mtime asc


## 10.3

- [ ] ```dataview 
	task where contains(tags, "2024-10-3")


## 10.4

- [ ] ```dataview 
	task where contains(tags, "2024-10-4")




%% kanban:settings
```
{"kanban-plugin":"board"}
```
%%