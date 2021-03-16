# Pre-work - *Memory Game*

Super Ultra Memory Game is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Charlie Taylor

Time spent: 5 hours spent in total

Link to project: https://glitch.com/edit/#!/cuboid-instinctive-fuchsia

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
https://recordit.co/NQUNC0H6c9


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I used https://www.w3schools.com/JS/js_random.asp to remember the syntax of the random function to make each game have unique button pushes.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
I had a bit of trouble with the logic at first for the game, as I am not as familiar with JavaScript as I am with Python or C++ so the if statement
trees were a bit hard to read at first. After tracing through the code a couple times it made more sense and I was able to write most of it on my own
while referencing the prework instructions. Making the logic required understanding of all of the functions from the prework page and how they are each
used together to make the game work. I have used HTML/CSS before as well but it's been a long time so messing around with the provided code and seeing
how everything meshed together was a bit of a challenge, but it came together pretty quick. The harder part was when I tried to implement the increased
playback speed and had to figure out which function had control over it and tweaking the scalar applied to the wait time so that it got faster at a rate
that wasn't too fast. Adding that took a bit and making the button sequence each time just took a quick search on how to use the random functions built
into JavaScript to be able to make random integers fill the sequence arrray.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I am more curious about what available libraries there are to make development faster and more functional, it took a while just to make a webpage
with 4 buttons so I bet it takes much longer to make a fully fledged one. I would also like to dive a bit deeper into JavaScript and learn more about
higher level features like classes and object oriented programming. Even with somewhat simple tools I was able to make a customizable memory game with
ease, so I can only imagine what could be possible with some of the code that others have already made. I hope to learn more about the possiblities of
working with the front and back end of websites and seeing what is possible with the tools available to me.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to work on the project I'd like to add customizations to it for the user to be able to play how they like. I'd add menus that would let the user
choose how many buttons to play with, whether or not the playback sped up each turn, and time limits for choosing the correct pattern. It would require a bit more research
on how to make new buttons appear through JavaScript and how to give them new and unique colors/sounds so that the game wouldn't get confusing. I think adding that would allow
users to play more to their skill level and make it more fun for more people. There could also be a game mode where it plays games back to back in increasing difficulty where a
button is added each time the player wins and the speed of the playback increases as well. Either of these would be fun to do, and I would like to learn more skills during this
internship to be able to flesh them out.



## License

    Copyright Charlie Taylor

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.