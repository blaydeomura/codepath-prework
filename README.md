# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Blayde Omura**

Time spent: **7** hours spent in total

Link to project: (https://glitch.com/edit/#!/repeated-meowing-durian?path=README.md%3A1%3A0)

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
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Design: This game playfully acts as a pseudo Salesforce assignment where the player is the applicant and the game is the first stage of the interview process. Each button represents a Salesforce core value. Hidden under each button is a Salesforce character that corresponds to that core value. If the player wins the game, they move onto the next "interviewing level." If the player loses, they can apply again next year. 

## Video Walkthrough (GIF)


![]()![](https://i.imgur.com/wTAi7gw.gif) 

(above) Partial walk-through of pattern. Working web page with correct buttons.

![](https://i.imgur.com/Ljltq35.gif) 

(above) Losing twice, and on the third time, end game.

![]()![](https://i.imgur.com/xKE6A1U.gif) 

(above) Playback speeds up + end game!

![]()![](https://i.imgur.com/1O93b4n.gif) 

(above) Salesforce characters under buttons that correspond to Salesforce's core values.


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[Adding images to glitch](https://mica-web.github.io/learn/workflows/add-img-glitch), 
[Uploading images to glitch](https://www.youtube.com/watch?v=XKUPuGXkpTY), 
[Salesforce hex colors](https://encycolorpedia.com/1798c1), 
[Formatting colors](https://www.rapidtables.com/web/css/css-color.html), 
[Placing images into html](https://www.delftstack.com/howto/html/html-button-with-image/https://www.delftstack.com/howto/html/html-button-with-image/), 
[Img syntax](https://www.w3schools.com/tags/tag_img.asp), 
[Font size format css](https://www.w3schools.com/cssref/pr_font_font-size.asp), 
Yordanos from USFCA CS peer tutoring center: showed me the “background: url…;" syntax.


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[The biggest challenge I encountered during this project was placing an image into the game buttons. At the beginning of this optional step, I felt very intimidated because I did not know where to start. I came to the conclusion that I need to import an image to the assets section of glitch, declare it in html, and style it in css. The problem was understanding how to connect the img in html into the css file so I could properly style it. I spent at least an hour searching the web on how to properly implement the image into the html and then style it in css. I eventually got the point to where I had the img showing on the button, and had it disappear when the button was clicked. The problem with this was that it should have been the opposite way around. The img should be hidden and only appear when the button is clicked. I continued to mess around with the css display properties, but that did not work out. 
    This optional step was very important for me to implement because it significantly added to the story/design of my project. This was because I wanted each pillar of Salesforce’s core values to correspond with a character that represented those values. 
    After not being able to figure it out myself and through countless internet searches, I signed up for a computer science peer tutoring appointment here at my university in order to overcome this challenge. My peer mentor was not entirely versed with css and html, but we scanned the web together and found a plausible solution. Instead of changing the color of my background to a different color when each game button was clicked, I would change the background color to an img of each Salesforce character. 
    It was a seemingly simple fix, but I spent a significant amount of time trying to figure it out myself. But through these troubles, I was able to learn how to leverage support from on campus resources. This solution reinforced the value of collaboration and that sometimes it’s best to seek advice from others rather than completely relying on myself.] 


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[I’m curious as to how an online commerce store works with inventory, payments, and a virtual shopping cart. I have only touched the surface of how a website may visually look, but I can see how html and css can create complex website designs. 
But I am now curious as to how an inventory of items are stored. If we are using a website like Amazon, where do we store that massive amount of data?
I am also curious as to how payments work and how they connect to a bank. I see how a payment page may look as a design, but what code is required to be written for a bank to be connected to an online payment page?
And my final question has to do with the online shopping cart aspect of an online store. How does one store information about what items were placed in a cart and can be accessed at a later date? Are the items in the cart placed in a txt file and read back into the website when asked?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had more time on this project, I would slow down the clueHoldTime function and make the amount of times the pattern plays unlimited rather than eight times. The reason for this is because I would like to create a global leaderboard for players (in this case, applicants) to compete against one another. 
    I would also like to add different levels to this game. For the sake of following my project’s theme, the next level would be the next stage of an interview process. 
    And the final attribute I would like to add to this project is an enhanced ending page. On this ending page, there would be a section where players can write constructive feedback in order to improve their user experience and fix bugs in the game. Players also have the opportunity to recommend different game modes. This page is important because it deals with customer success. This ending page allows for customer satisfaction while also incorporating innovative components brought to us by the players themselves.]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/35a349a82dc64ce1bc8b2826c2390c4c)


## License

    Copyright Blayde Omura

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.