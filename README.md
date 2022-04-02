# Pre-work - Sound and Color

Sound and Color is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Gisselle Petty

Time spent: one hour spent in total

Link to project: (https://polydactyl-fast-partridge.glitch.me/)

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
![https://media3.giphy.com/media/LkdPPENuM6209D5hFg/giphy.gif?cid=5e214886be76a9fc7ddd5a3b17c488748a1e94add4521a37&rid=giphy.gif&ct=g]
![https://media2.giphy.com/media/3B6eYXEmrfqu7dt4bs/giphy.gif?cid=5e214886be76a9fc7ddd5a3b17c488748a1e94add4521a37&rid=giphy.gif&ct=g]


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[No other outside resources]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[A challenge of mine in creating this submission was game logic. Which is something I'm having a difficult time right now in another project 
of mine, an old recreation of Pong in C++. For this project, it was thinking of how to organize and check for which buttons were being pressed
but also making sure that the sequence was being run correctly. The last time I programmed a web app in Javascript was in an introductory course
in high school in 2020. Currently, I work in C++. So because C++ is very strict when it comes to comparing data types. I had a difficult time 
thinking of a way to compare the button being referenced from the HTML file in the function guess because I didn't realize we were still comparing
an integers. This was also my first time linking Javascript to an HTML file so that for me could perhaps be my biggest challenge, but nonetheless
I was excited for this exercise because I've been always curious how the two coincide. I have worked with HTML before as I've made my own website
but using Javascript has show me a different level web development which was definitely something new for me to experience. I overcame both of my 
my challenges by rereading the HTML code and realizing that the onclick tag from the colored buttons was tying the function guess and its numbered 
parameter to the functionality of whether the playing or winning or not. Then from there I checked for various scenarios using if statements. As for
my second challenge, I focused on my progress and my fascination with Javascript rather than being intimidated because I had worked on it before and
also because the Glitch learning environment seemed beginner friendly.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[As for web development, as an undergrad hungry for work and experience in the field I want to present my work as professional.
With that comes the task of designing your own website to post your resume and projects. However, a problem I am currently facing
and would love to solve in the future is how to make my site mobile friendly. Its most likely a simple answer but I just haven't
found the right one yet. Other questions I have are how can I use Javascript and HTML in a more advance way to the point where I can
produce more complicated games on a website, such as a past project of mine which was a burger flipping game in C++.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had a few more hours to work on this project, I would spend them changing the tune of the buttons and maybe add a 
different game mode. Similar to one of Nintendo's DS game, Brain Age, I would add a similar mini game where users are given the 
name of a color, but they're supposed to match what color of font the word is in, rather than what the word spells out. For example,
the word Blue comes out on the screen, but it is written in yellow font. The correct answer would be the yellow button.]



## Interview Recording URL Link

[My 5-minute Interview Recording] https://ucdavis.zoom.us/rec/share/2Vv6g4koGSA_X4rEfTjhaHuh26NF2rW8oNRqmZrYXLwbHR87gMHTiz8hW5eeZBWl.vIGKPbO2auj02WCS?startTime=1648880180000


## License

    Copyright [Gisselle Petty]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.