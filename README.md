# Pre-work - *Memory Game*

Light and Sound Memory Game is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Michio Sekiguchi

Time spent: 4 hours spent in total

Link to project: https://magenta-eggplant-polo.glitch.me/

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

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![]https://cdn.glitch.global/6d360624-937d-44e7-9506-2be9b607e6b2/game.gif?v=1650604169665


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://www.w3schools.com/jsref/

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The main challenge I had to overcome was adding images to each of the buttons. I did not know how to add the custom images to the buttons
so I seached through the JavaScript reference section of www.w3schools.com and learned about the html styling to the buttons
that would allow me to just set the background of the buttons to the images. I then added the images of the correct width and height.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I'd like more experience with web design to see how current popular websites are styled and designed. This introduction is clear to follow
and learn from so I am curious as to what the differences are between this and how popular websites are made.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
My biggest issue with the application is that the buttons can be pressed and the guesses can be made before the sequence of clues are
finished playing. I would fix this by using the interval functions to keep track of what part of the game the player is in. I could then allow or don't allow
the player to make guesses based on the time. Tracking what part of the game the palyer is is could also allow a changing text instruction to be displayed
telling the player what to do at the moment and how much time they have left to guess.



## Interview Recording URL Link

https://www.loom.com/share/797be98eb2604d7fb739e28fff03cd71


## License

    Copyright [Michio Sekiguchi]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
