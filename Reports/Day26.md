# Day 26

Today I improved the different states of the Pomodoro timer. The Focus page now shows if the timer is ready, running, paused, or completed. This makes it easier for the student to understand what is happening without checking only the button text. 

I also checked the timer controls more carefully. Once a focus session starts, the student cannot change the course or switch between Focus and Break mode. This is important because changing the course after pausing could create incorrect session information in the history.

The Reset button returns the timer to its starting time and unlocks these options again. I also checked that the timer cannot be started after it reaches 00:00 until it is reset.
