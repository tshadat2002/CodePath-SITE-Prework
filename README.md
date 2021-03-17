# CodePath-SITE-Prework
# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **NAME**

Time spent: **#** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](http://g.recordit.co/1eYoGa2MoJ.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[w3Schools, developer.mozilla]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[One challenge I encountered in creating this submission was definitely writing the conditional logic inside guess. Up until this point in the pre-work, I was pretty much told what to code and how to code it. This was the first time in the pre-work where gears changed and I had to figure out the logic myself. At first I thought it was going to be easy, and the code I had to write would be one line. I was wrong. I realized that the only way I was to figure out the logic was to go through the written code line by line from each file in order to become familiar with what was going on. I used my notebook to take notes on what was supposed to happen in the code and this helped a lot. I figured out that I had to write a conditional where if the user clicked the correct button, something would happen, and if not, they would lose the game (calling the loseGame function). Slowly but surely, I began to piece together the logic. It was a tedious process but doing this helped me solve the problem. ]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[How would I set up a website to accept payment securely? What frameworks or software would I use to do this? How would I know when to use what frameworks? Can I build a website using both Javascript and Python together? What is the best strategy in figuring out the logic for certain implementations in a web application? In what scenarios are the concepts of data structures and algorithms used in web applications? Does the length of my code affect the loading time and efficiency of my website? How do I make sure my website shows up first on Google? How can I officially host my website with my own domain?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had a few more hours to work on this project, I would add features that would improve the quality of the game as well as design. For example, if the user clicked the wrong button sequence, I would configure the game so that everything on the screen turns red (the background color), and change the text in the heading of the game to say “You lost” with some instructions below saying how to start the game again. Further, once the user decides to start the game again, everything on the screen turns into the default setting. Another feature I would like to change in the game would be its pattern. I want there to be a random sequence of buttons rather than a fixed sequence as well as make the game infinitely continuous. Lastly, if I had a little bit more time, I would use some Javascript to change the way to start the game. Rather than using a start and stop button to initiate and stop the game, I would like for the user to start and stop the game simply by pushing down a button on their keyboard. ]



## License

    Copyright [Taohid Shadat]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
