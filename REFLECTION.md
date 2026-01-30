# Reflection – Daily Schedule Simulator


## What was your approach to designing the schedule?
Explain how you chose your activities and what made them personal or interesting.

I love playing tennis, so adding it alongside learning JavaScript and my usual 
daily activities made my simulation feel more authentic. 

## What was one challenge or unexpected behavior you encountered?
Describe anything surprising that happened when you tested the timing.

Initially, I used standard setTimeout callback code that was nested and difficult 
to read. So I switched to a Promise-based approach, which helped me to better 
structure my code.

## What does this assignment teach you about async code?
Compare this to a regular script that runs top to bottom without delays.

It taught me that an async function returns a promise and its body awaits other
promises in a way that looks synchronous - making it easier to read. 

## What creative element did you add?
Did you add randomization, surprise content, a twist, or other enhancements?

I decided to add a list of movies and a list of moods. So after the movie, the 
simulation can pick a random movie and associate a random mood with it. 

## How does this project simulate or differ from real-world schedules?
Explain how well your simulation represents how time works in real life.

It simulates real life by maintaining a strict ratio where 1000 milliseconds 
equals 1 hour of real-life activities, like 4000 milliseconds = 4 hours 
of real-life activity.  