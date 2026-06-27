# ChatBot3
A WPF desktop chatbot built with C#. Combines cybersecurity education, task management, a quiz game, and activity logging in a single GUI. 

No database or console used - 100% WPF as per Part 3 requirements.

Project Files
This project consists of 2 main files you provided:
1.  `MainWindow.xaml` - The UI layout: Chat panel, 3 tabs for Task Assistant, Quiz Game, and Activity Log
2.  `MainWindow.xaml.cs` - All logic: NLP, Task CRUD with in-memory lists, Quiz, Activity Log, Voice + ASCII

Rubric Features Covered


**Task Assistant + Reminders** `CyberTask` class + `AddTask`, `GetAllTasks`, `CompleteTask`, `DeleteTask` using `inMemoryTasks List`. GUI in Tab 1 
 **Quiz Game** 
`QuizQuestion` class + `LoadQuizQuestions()` with 12 MCQ/TF. `QuizPanel` in Tab 2. Instant feedback + score 
**NLP Simulation** `GetResponse()` uses keyword lists: `addTaskKeywords`, `viewTaskKeywords` etc. Handles `remind me to`, `show activity log`
