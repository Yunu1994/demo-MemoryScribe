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
- [ ] 22:11 test no selected text
- [ ] 23 modified
- [ ] sleep


## 9.30

- [ ] ```dataview 
	task where contains(tags, "2024-9-30")
- [ ] 12:32 group work draw the paper prototype
- [ ] 13:08 study do some lab
- [ ] 13:09 in lec with another group finish play and test
- [ ] 13:11 test  finish play and test## 10.1
- [ ] 13:16 study first 10 pages of slides draw the paper prototype
- [ ] 13:17 AA AAAA
	AAAA
	AAA
- [ ] 13:43 2310 lab STUDY the week 
- [ ] 13:43 test2 
finish play and test
## 10.2

- [ ] ```dataviewjs
	// 获取所有页面的任务
	let tasks = dv.pages()
	  .where(p => p.file.tasks && !p.file.path.includes("kanban")) // 确保页面包含任务
	  .flatMap(p => p.file.tasks) // 提取所有任务
	  .filter(t => t.text.includes("2024-10-2")); // 筛选未完成的任务
	// 清理任务文本，去掉#后面的内容
	tasks.forEach(t => {
	  t.text = t.text.replace(/#.*?(\s|$)/g, '').trim(); // 去掉#及后面的内容
	});
	// 显示任务列表，保持链接功能
	dv.taskList(tasks);
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
## 10.18
- [ ] 13:21 s finish play and test
- [ ] 13:29 1 