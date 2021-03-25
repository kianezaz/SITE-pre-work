# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Kian Ezaz

Time spent: 3 hours spent in total

Link to project: https://glitch.com/~tin-purple-driver

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess


## Video Walkthrough

Here's a walkthrough of implemented user stories:

![](https://cdn.glitch.com/1d7d95cb-e5e3-4bb3-8600-2326c6282ee6%2Fezgif.com-video-to-gif.gif?v=1616635630445)

![](https://cdn.glitch.com/1d7d95cb-e5e3-4bb3-8600-2326c6282ee6%2Fezgif.com-video-to-gif-2.gif?v=1616636213902)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

Stack Overflow: Used to solve the problem of having no audio play upon pressing any button
w3schools.com: Used to gain a better understanding of the various selector options CSS provides, what exactly they do, and when to use them.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

A challenge I encountered in creating this submission was understanding how exactly the functions that define the game all tied together, especially when the JavaScript functions are intertwined with the 
contents of the html and css files. For example, the handling of events, such as the pressing of a button, were required to be defined in JavaScript, but are actually called in the html file where there 
is a different syntax. To add on, the behaviors of some of the functions that were carried out were new to me and forced me to pause and learn exactly what the function and what parameters it takes in to 
truly understand the flow and behaviors of the game. This was the case for the setTimeout function; only by understanding its behavior and the arguments we choose to pass in could I follow along with the 
flow of the game. Another aspect of this submission that challenged me was understanding the logic behind the styling rules in css. The various forms of selector references, such as one seen by 
“#gameButtonArea > Button” as well as when to use such rules forced me to ask and test out why a certain rule was used the way it was. Overall, the challenges were a result of much unfamiliarity of the 
interaction between the various languages and functions/syntax which I overcame by spending time reading documentation and the helpful information provided on the walkthrough to be able to explain what 
exactly the code is doing when I press some button in the game.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

Upon completing this submission, I came to wonder how web applications with significantly more content are maintained/organized. For example, how does Amazon organize the enormous amount of data and ensure 
the right data is presented upon the click of a certain button on their website? They must somehow integrate significant reusability of their code to account for the seemingly infinite possible pages the 
user is redirected to. Another I came to wonder is how exactly can data be saved from one session on the web application to another? This can again be seen with Amazon since users must create accounts, and 
their data (such as recent orders) are saved after they log out. I imagine many different technologies are required to be integrated together in order to ensure the maintaing and privacy of such data for
all users. Finally, I wonder how popular websites handle such heavy traffic on a regular basis while remaining completely stable.  

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours, I would try to figure out how to implement a game mode that increases the difficulty of the original game so that as the user progresses through each round, the colors of the 
buttons increasingly blend with the background to the point that in the last round, the distinct colors of the buttons are not visible and the player has only the sound of the buttons to rely on. Rather 
than being able to use both eyes and ears, now the player will have to increasingly rely on their ears. Another idea I am interested in integrating is displaying some form of distractions in each round to 
make it more difficult for the player to remember the order of the buttons. This could be done by displaying random images for a couple of seconds when handling button clicks.



## License

    Copyright Kian Ezaz

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
