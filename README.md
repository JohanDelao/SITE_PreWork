# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program and FTL Program.

Submitted by: **Johan Delao**

Time spent: **5** hours spent in total

Link to project: https://glitch.com/edit/#!/universal-spark-seeker

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

![](https://cdn.glitch.global/c710925a-01e7-42d4-846d-2049e0c6fcf2/siteGIF.gif?v=1647919626363)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. <br>
   **Only used the given pre-work step guide and prior knowledge.**

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) <br>
   **A challenge I encountered, outside of coding, was finding the time to work on this project outside of school due to various commitments. However, I was able to squeeze it into the weekend days before I went to work. A challenge I encountered was that all the buttons that were in the current pattern would light up at the same time, confusing the user as there could be multiple choices to pick. After looking over my code I realized I put "delay += clueHoldTime" and "delay += cluePauseTime" outside of the for loop in function playClueSequence, making all the clues light up at the same time without delay.**

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) <br>
   **Some questions that I have about web development is the different packages that can be used for applications. After seeing the ease of use of this particular audio package, I am looking forward to seeing what other kind of packages I can use for other projects. Another question I have is about the use of JavaScript, HTML, and CSS, are those languages still the primary technologies for web development? Or is the React.js framework more popular?**

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) <br>
   **If I had a few more hours to work on this project I would have spent them on making the patterns be random everytime the user would play the game, I think that is the best feature to add to make the game more interesting.**

## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/f985058188b74ff88a808f2280c752bb)

## License

    Copyright [JOHAN DELAO] 
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
