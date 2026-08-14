# Day 28

The course list can now be saved locally on the device. Before that, attendance changes disappeared when the app was closed. I also connected the course data to the LocalStorage helper from the previous day. When the student adds or removes an absence, the updated course list is saved automatically. When my app starts again, it first checks for saved courses and loads them if they exist.

If the app is opened for the first time and there is no saved data, it still uses the same mock courses. This keeps the app simple and prevents an empty Lessons page.
I also made sure that course IDs stay the same after saving
