# Day 22

I made Focus page more useful today because I added course selection for Pomodoro sessions. Before starting the timer, the student can now open a menu and choose one of the courses that already exists in the app, such as Database Systems, Software Engineering, or Algorithms.

The selected course is shown directly inside the timer card, so it is always clear what subject the student is studying. I also connected the course picker to the PomodoroSession model instead of creating another separate list. This means the Focus page uses the same course data as the other parts of the app.

While the timer is running, the course menu becomes locked. I added this because changing the subject in the middle of a focus session could make the session information incorrect. After pausing or resetting the timer, the course can be changed again.
