# Day 23

This time I worked on what happens after the Pomodoro timer reaches 00:00. Before this change, the timer stopped, but the app did not remember that the student had completed a focus session. I also added a list of completed sessions to the ViewModel. When the countdown finishes, the app creates a new session using the selected course and the 25-minute duration. It also increases the number of completed rounds. I made sure that the same session is not added more than once after the timer stops.

The Focus page now has a small Focus Progress card. It shows the total number of completed rounds and information about the last completed session, including its course and duration. I also changed the page to use scrolling so everything fits better on smaller screens. Next, I will add focus and break modes to the timer.
