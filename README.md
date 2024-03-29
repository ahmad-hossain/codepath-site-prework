# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Ahmad Hossain**

Time spent: **24.5** hours spent in total

Link to project: [https://glitch.com/edit/#!/possible-spangle-september](https://glitch.com/edit/#!/possible-spangle-september)

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
* [X] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [X] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [X] **Accessibility Mode** is made so that **visually impaired people can play the game**. All button sounds along with corresponding button number are played through speaker before game starts. 
Keyboard shortcuts are used to guess respective buttons and to start/stop game.
Lives remaining are spoken aloud whenever they are changed.
- [X] A random **image/gif of a cat** is set on a button every time it's clicked using an **API GET request**
- [X] Number of **Heart emojis** represent lives left
- [X] Heart emojis have a **beating animation**
- [X] Start & Stop buttons use a **Material Design Component Button**
- [X] Game UI is centered on screen
- [X] User can toggle between **Light Mode** and **Dark Mode** using **Material Switch Component**
- [X] **Custom Font** is used from Google Fonts style sheet
- [X] **Custom background color** is used
- [X] User can **click a button to change the background color** using given color palette buttons

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

### Accessibility Feature Videos (With Audio)
**NOTE:** Keyboard shortcuts are being used in the videos to interact with the game

**Winning Game**: [Link](https://drive.google.com/file/d/1aPKmbEpXC0DQoTiKXNKlS4ZMZv7YMNHh/view?usp=sharing)

**Losing Game**: [Link](https://drive.google.com/file/d/1lOk72RR746W4UG5aCFciTMTdmYaBCXuH/view?usp=sharing)

### Game Win
<img src='https://thumbs.gfycat.com/FrailHoarseDalmatian-size_restricted.gif' title='Video Walkthrough' width='400' height='400' alt='Video Walkthrough' />

### Game Lose
<img src='https://thumbs.gfycat.com/ElementaryObeseGonolek-size_restricted.gif' title='Video Walkthrough' width='400' height='400' alt='Video Walkthrough' />

## Reflection Questions
**1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.**
* Used Google to find the CSS syntax for increasing border-width for an element. I increased the border width for all buttons.
* Used Google and W3Schools to learn about styling background images.
* Used Google & Stack Overflow to find out how to reset the progress of audio element rather than just pausing it. 
* Used Material Design website & Github to figure out how to add a Material Design Component
* Used W3Schools to learn how to display a heart emoji
* Used Material Design website to get html element for Material Switch
* Used [this](https://css-tricks.com/snippets/javascript/javascript-keycodes/) website to find keycodes for keyboard keys so that I can setup listeners
* Used code from [this](https://www.sitepoint.com/delay-sleep-pause-wait/) article to help me make my code sleep for some time
* Used [this](https://stackoverflow.com/questions/53748420/javascript-speechsynthesisutterance-speak-out-numbers-properly) StackOverflow to show me how to speak numbers aloud via javascript
* Used [this](https://stackoverflow.com/questions/53573568/synchronous-execution-in-javascript-with-speechsynthesis-speak) StackOverflow post to learn about the Speech Synthesis onend callback.
* Used [this](https://stackoverflow.com/questions/6976486/is-there-any-way-in-javascript-to-focus-the-document-content-area) StackOverflow post to figure out how to remove focus from an active element. I used this to prevent the Accessibility toggle switch from staying focused after it has been turned on, allowing the user to immediately begin using keyboard shortcuts. 
* Used [this Google Font](https://fonts.google.com/specimen/Varela+Round#standard-styles) to get the style sheet link for the Varela Rounded Font
* Used [this](
https://stackoverflow.com/questions/49680484/how-to-add-one-event-listener-for-all-buttons) StackOverflow post to learn how to populate a list of elements from a js query on the DOM and create a click listener for each item. I used this to programatically create click listeners for each theme button in the parent container div.
* Used [this](
https://stackoverflow.com/questions/12576084/getting-the-real-background-color-of-an-element) StackOverflow post to find the syntax for getting the background-color of an element via js. I used this to get the color of the button that was clicked in the theme-section, and set the background-color using that.
* Used [W3Schools](https://www.w3schools.com/css/css3_animations.asp) to learn how to create CSS animations.

**2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)**

A challenge I encountered in creating this submission is finding out how to add some padding inside the buttons so that the cat images don’t take up the entire space. I had tried multiple solutions such as setting padding, margins, and background-size. However, I wasn’t able to find what I wanted. Therefore, I began doing research online to see how others have solved this problem. It did take some patience, but eventually I stumbled upon a solution through my research. If I wasn’t able to find a solution after some time, I would have asked for help in an active community such as #webdev on Slack, Stack Overflow, or a Discord server for Web Development.

**3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)**
* It was mentioned in the lesson that you can apply a certain CSS style using div#someIdHere. I'm curious why you would need to specify the kind of element for the ID, as there can only be one kind of ID in the entire file. My first thoughts are that it would be sufficient to just use #someIdHere rather than specifying the type of element as well because it seems redundant.
* I would like to know about the different architectures for keeping script code and CSS styles organized. By looking at my project thus far, I can see how it would be difficult to read through all the code and CSS Styles just to add a new feature. The Web Developer community must have developed certain strategies to help with this, and I'm very interested in the different methods.

**4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)**
* I would spend time organizing the script code into different files so that everything is very easy to understand. For example, I would put all the audio related code into one file and give it a relevant name to keep everything organized. This would help me find out where I would need to add code if I wanted to add a new feature in the future.
* Another feature I would work on is improving the CSS styles. I would like to take a look at different websites or even the Material Design docs and gain ideas about the colors and styles that they use for similar layouts, and improve my project to my liking.
* I would add more log messages. If I add features in the future, it would be difficult to debug if I don't have an idea of what is going on in my code. It's better to spend a few seconds in the present rather than hours in the future adding log messages.
* It would be great if I could add unit tests to test the business logic for the game, because as more features are added, even with log messages, it would be difficult to debug. Unit tests would help me find out when something is wrong and where it is occurring.
* I would like to change the way the logic for the game works by making it more Object-Oriented. I would have a Game class whose properties represent its current state. The class functions would be able to handle related business logic and interact with the states.

## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/a861a27a378d4dd4b194d4bc97420152)


## License

    Copyright [Ahmad Hossain]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.