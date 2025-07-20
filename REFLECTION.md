# Izarra Villareal CS 81 JavaScript Module 7 Assignment 7B: Daily Schedule Async Simulator

# Reflection – Daily Schedule Simulator

## What was your approach to designing the schedule?
I chose my activities from various things I try to accomplish within my daily life. The bulk of my day is work, but I try to fit various healthy, and necessary personal growth, tasks into my busy work schedule as well. Some of these personal activities are things such as transgender voice training, yoga, a walk, and practicing the guitar.

## What was one challenge or unexpected behavior you encountered?
When I tested the timing in Chrome, using the LiveServer option in VS Code, I noticed that the timing starts all over if I change focus away from that tab in my browser and then go back to it. The simulated activities start all over again. I am assuming that Chrome reloads or refreshes when this happens. I also noticed that the timed delay is relative to the loading of the webpage and not to any specific time of day.

## What does this assignment teach you about async code?
This assignment teaches me that async code, once it begins, runs regardless of the rest of the webpage, and there are nuances to the usage of setInterval versus setTimeout. SetTimeout could be useful in waiting for various other things to occur first before executing another function. This would allow you to build upon dependencies with timed delays.

## What creative element did you add?
I added the random mood emoji to my simulated daily lunch break. It takes an array of mood emojis and appends one into the daily lunch break simulated activity.

## How does this project simulate or differ from real-world schedules?
Real world schedules do not always happen at exact delay intervals, they are subject to changes and cancellations. My simulation does not really accurately represent how time works in real life because the delays are mere seconds apart. There is no way I could possibly do these simulated activities within seconds. Time in this exercise is very specific and exact not leaving much room for unexpected changes. The time also operates relative to the loading of the page so it wouldn't exactly align with the real-world time of the activities being performed.