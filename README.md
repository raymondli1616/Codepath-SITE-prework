# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Raymond Li**

Time spent: **5** hours spent in total

Link to project: (https://glitch.com/edit/#!/water-playful-tyrannosaurus?path=index.html%3A1%3A0)

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
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
<br>1. Memory game is functional and responds with a "You Won!" message to indicate you have won.![](http://g.recordit.co/RG55rwQDxo.gif)
<br>2. Memory game responds with a "you lose" to indicate losing the game.![](http://g.recordit.co/uFaEjbVwCp.gif)
<br>3. Changing the elements to the HTML and having more than 4 buttons.![](http://g.recordit.co/luj0dAiVjp.gif)
<br>4. Memory game speeds up after each turn.![](http://g.recordit.co/Cp5G1n2VN7.gif)
<br>5. Memory game starts off with a different pattern each time.![](http://g.recordit.co/qR1K8iS4GC.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
<br>Markdownguide, W3 schools, Mdn

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
<br>While creating this project I definitely had difficulty creating and implementing the getRandomInt() function. The getRandomInt() function basically made it so for each game that is played the patterns are different. I found this function diffult to create and implement because I had to figure out how to get the the output of getRandomInt() into the array pattern. I overcame my problems by using Mdn to fully understand how to implement getRandomInt() so that the random int generated is between 1 and 5. Then using more online resources, I learned on W3 schools that in order to add the output of getRandomInt() into pattern, I had to use the push() method. The push() method made it so that each time getRandomInt() is called in the interation, it is added to pattern. This part of the code will be pattern.push(getRandomInt(5)). While creating getRandomInt(), finding out how to limit the range of Math.random was also a bit difficult. I had to write the function as getRandomInt(max) because 5 will be referenced in startGame() and it will be the number generated will be 0 to 4. I figured out that I would need to add 1 to the generated number in order to avoid having 0.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[YOUR ANSWER HERE]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[YOUR ANSWER HERE]



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Raymond Li]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
