# Day 07

Today I added the attendance buttons.
Now, when I open a course detail page, I can press Add to increase absences and Remove to decrease them. The progress bar and numbers change on the screen after pressing the buttons.

I also added simple limits. The absence number cannot be less than 0, and it cannot be more than the allowed absence limit.

For repeated courses or courses without attendance tracking, the buttons do not work. This makes the app logic more correct.
Today I learned a bit more about Binding in SwiftUI, because the detail page needs to update the real course data.
