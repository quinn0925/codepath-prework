# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Quinn Kanner**

Time spent: **7** hours spent in total

Link to project: https://glitch.com/edit/#!/aged-tangible-cub

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
![](https://i.imgur.com/tY3B3kG.gif)
![](https://i.imgur.com/cPBCsF3.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://www.the-art-of-web.com/javascript/creating-sounds/
https://w3bits.com/rainbow-text/
https://www.w3schools.com/
Stack Overflow (obligatory)

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The biggest challenge, for me, in this project was the creativity and aesthetics of it. Most, if not all, of the projects I have done to date have been I/O algorithmn focused, with the only creativity in how you choose to solve the problem. Moreover, aesthetics is not my strong suit, and usually my focus is on creating a project that works. However because so much of the code was provided I wanted to challenge myself a bit and play with the creative appearance of the game. I first decided that rainbow colored text would look pretty nice, but then I had to change the background color and text color for the best effect. I then thought that creating the buttons in rainbow colors would also look nice, give a "rainbow" effect to the game, but I then had to figure out the best way to make the each button look different when activated. I figured this out by using the CSS property "filter" and lowering the brightness initially, then increasing the brightness. However, some of the darker colors needed an even greater brightness increase, while the lighter colors needed less of an increase. This was frustrating at times, because from a practical standpoint the % change in brightness for each button has no impact, yet taking this project as a whole, the aesthetics are quite important for the user experience. I overcame these difficulties simply by my desire to implement this project as a "rainbow" game, and I researched how I could make it work, and then made it work.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
    How do you do it? 
Now that I understand basic web development, I am only more confused about how some websites are so increbily complex. For the past few months my company has used Salesforce Lightning as our CRM, and I really want to see the source code on that. I am curious about how all the different features are implemented. Are the different list views just a more complicated version of what I did using .hidden? Does the webpage actually do anything, or is it simply a display for the user to interact, like a much more complicated keyboard? If so, what is facilitating the interactions between the front-end and back-end? From an aesthetic side, a site that comes to mind is Apple. That website has some amazing transitions/animations/effects on almost every page, and they work so seamlessly. I wonder if that is implemented using a library or something similar? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I would spend more time making the program unbreakable. I noticed for some things like the font, for example, backup fonts were usually specified in case the users computer does not have a certain font installed. However, I am sure there are many other aspects of this program that could "break" under certain conditions that I would guard against. Additionally, I would have liked to add better sounds for the buttons, but I did not fully understand how to play tones, other than the basic implentation of a single tone for each button. Overall, I would have wanted to work on the JavaScript more to create better algorithmns.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://photos.app.goo.gl/2wBV2ZN3dYtEQvm67)


## License

    Copyright Quinn Kanner

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
