# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Muhammad Umair Jamil**

Time spent: **9** hours spent in total

Link to project: (https://glitch.com/edit/#!/mulberry-tidy-porter?path=script.js%3A77%3A33)

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

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![CodePath Project - Light and Sound Game](https://user-images.githubusercontent.com/99949345/161141945-01862056-e733-4e96-97a8-eac3edff5737.gif)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[All the resources that I used were already provided in the prework. The YouTube videos helped me a lot by guiding me step by step on how I should complete the tasks. I did use google to help me out understanding a little bit of one the setTimeout() function.]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[One of the challenges that I faced was to create the guess function. I was having a challenging time trying to figure out how I can use the “pattern.length” in the if condition with “progress”. Once I looked back at my “if” conditions, I realized that I can set the conditions of guess counter to be equal to progress. Then compare if progress is the same as pattern.legth -1. If so then “winGame()” is called which runs the stopGame() function that stops the game and runs the alert for “Game over, you won!”. I was also having trouble with the “playClueSequence” as it had setTimeout() function and I did not know what setTimeout() does, so I had to Google my way and figure out how it is used and what is the purpose of having a setTimeout function. One of the other problems I had was to figure out how to convert the video to a GIF and how to set up the github repository and by watching the YouTube videos provided in the prework I was able to easily figure out how do I go about making the repository and exporting the files from glitch to my GitHub repository.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[I really did enjoy and learned alot just by the prework itself and I want to learn even more. Will we be taught how to make web pages interactive and user friendly? I also want to know if we will be learning to make a web page responsive for all devices and platforms. Is it possible to make a 2D game with lots of charactes and add sound effects on a web page? If so will we be learning how to make that game? Will I be allowed to rework on this Memory game project and make it better then it is right now?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[I would rework this project to add animations and some bachground effects such as shadowing and enlarging as the mouse pointer hovers over the buttons. I would add a difficulty level that the user can choose and depending on the dificulty the gme speed will increase and so will the game buttons. I wouls also add pictures to the buttons so that it will easier for the user to visualise it and remember is easily.]



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Muhammad U Jamil]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
