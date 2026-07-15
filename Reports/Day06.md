# Day 06

Today I worked on the attendance logic of my iOS app.

Before this, the courses only showed attendance information, but the values could not really be changed. Today I made the Course model editable, so the number of absences can be updated later from the app.

I added simple functions to add and remove absences. I also added some limits, so absences cannot go below 0 and cannot go above the allowed absence number.
I also repeated courses and courses without attendance tracking cannot be changed. This is important because some courses should not count attendance.

Today I practiced writing logic with Swift models and ViewModels. On Day 7 I will add buttons in the UI so the user can increase or decrease absences from the screen.
