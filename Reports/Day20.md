# Day 20

The Focus page now has a working Pomodoro timer. Before this, it only showed the text 25:00 and the button did nothing. I added a real countdown that updates every second.

When I press Start Focus, the timer begins and the button changes to Pause. I can pause the timer and continue it again. The countdown also stops automatically when it reaches 00:00.

While working on this part, I learned how to use @State, Timer, and onReceive in SwiftUI. Next, I will add reset controls and improve the timer states.
