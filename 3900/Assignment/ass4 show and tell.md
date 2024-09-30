- [x] write script #2024-9-30 

日记的重要性
We all know how valuable it is to keep a journal—whether it’s for self-reflection, tracking progress, or just keeping memories alive. But here’s the thing: keeping a daily journal can be a bit tedious, right? It’s easy to forget or not have time for it. That’s why writing digital diary and automating the process is so important.
	自动化创建日记的重要性
	By streamlining the way we create journal entries, we remove that extra mental load of having to remember to sit down and write every single day. Plus, automation helps to ensure consistency. And the more consistent we are, the better the outcome for long-term journaling. It turns into a habit that can add real value to our lives without much effort. and later you will find out that the long-term dairy you keep will serve as the key database for our next feature: emotional chatbot.
	最终版实现
	Now, let me walk you through what I’ve built using **Obsidian** and its plugins. This workflow has really optimized how I manage my daily entries and tasks.
		日记条目 ctrl+d value selected，capture到kanban
		the journaling process begins with a shortcut—just hit `Ctrl + D`, and both the input and the selected text gets captured into your Kanban board.
		you can stay fully immersed and don’t need to switch over to the journal board while working. Once you’re done, the board has a summary of your day’s work. With just a few small edits, your dairy is practically done.
		每日待办 写待办时标注tag，kanban查看并且可以跳转
		and the board not only acts as a summary, but also a task management dashboard. For your work notes, you only need to add date tags after every to-do. The Kanban board automatically tracks them, so you can view all your tasks in one glance. 
		When you’re ready to start working, you can jump straight from the board's to-do into the task page. Once you're done with the task, simply check off the to-do, keeping everything in sync with your board.
		周记视图 便于回顾
		Finally the board turns into a weekly overview and it's super convenient to reflect on what you've accomplished over the last week.
	仅是提及：我们也实现了更加自动化的日记生成，但是kanban的版本是效果最好的
	I also experimented with some more automated versions of this journaling system, but honestly, I found that the Kanban-based approach works the best for me. It’s simple, and yet it’s powerful enough to manage my entries and tasks without overcomplicating things.
展示onenote里我的2年日记，描述长期日记的强大之处
Just to give you a sense of how impactful journaling can be long-term, I’ve been keeping diaries for two years in **OneNote**. 
What I’ve come to realize is that consistent journaling isn’t just about personal growth—it’s about keeping memories alive. It’s like preserving those little joyful moments that you might otherwise forget. 
For example, I can look back at my entry from last September when I first played _Baldur’s Gate_. I can still recall the excitement of downloading it for the first time and the thrill of playing with friends. Journals like these act as a sort of permanent storage for your memories, and those moments are absolutely priceless.

问答
Q: Is it possible to change or customize the content in the Kanban board or QuickAdd?How flexible are the settings for the Kanban board and QuickAdd? Can I tweak them?
A: Both Kanban and QuickAdd are really flexible. You can go into the plugin settings and modify the templates or fields to suit your needs.

Q: Do you have to create each week’s entries manually, or is there an automated way to do that?
A: There’s a template with date placeholders that makes it super easy.

Q: Adding the minutes before each journal entry seems a bit cumbersome. Is there a way to streamline that?
A: the date and time placeholders in the templates are fully adjustable.