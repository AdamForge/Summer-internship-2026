# Day 30

The last part of the app that disappeared after restarting was the Focus session history. I worked on saving this history locally today.

When a Focus timer reaches 00:00, the app now saves a session with the selected course, the 25-minute duration, and the completion time. When the app opens again, it loads the saved history and shows it in the Session History section. And also I decided not to save a timer that is still running or paused. Only finished sessions are saved, because those are the real study sessions the student completed.

This made the Focus page feel more complete because the student can keep their study history after closing the app. Next, I will do final testing and make small UI improvements.
