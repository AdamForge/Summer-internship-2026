# Day 29

The main thing I worked on today was saving the exam and task data in the app. For exams, I connected the saving part to the Add Exam and Edit Exam screens. Now if I change the vize score, final weight, or exam date, the new information can stay in the app after reopening it.

I also worked on tasks because they have more actions than courses. A task can be added, edited, marked as Done, opened again, or deleted. I made sure these actions save the updated task list. At first, I noticed that the task detail screen changes the task in a different place from the main Tasks screen. I added the saving call there too, so the task does not lose its new status after restarting the app.

The app still shows mock data when there is no saved data yet. Next, I will work on saving the focus session history.
