# Day 27

Today I started preparing UniLifeGlass for local data saving. Until now, all the courses, tasks, exams, and focus sessions only stayed in the app while it was open.

I updated the main models so they can be changed into data that the app can save and load later. I also added a small LocalStorage helper file. It will help keep the saving code in one place instead of writing the same code in every screen.

I checked that the models keep their IDs when they are saved and loaded. This is important because the app needs to know which course, task, or session belongs to which item.

The app still uses the same mock data for now, so there is no visible change on the screens yet. Next, I will start saving the course list and attendance changes locally.
