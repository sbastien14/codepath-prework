# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Samantha Bastien

Time spent: 7 hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

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

- I wrote a function that randomly generates an array of 8 int values ranging from 1 to 4. This way the game creates a new pattern every single play. 
- I changed the colors of the bottons, the background and the writing to make it more aesthetically pleasing.

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/AprBOdJLTx.gif)
![](http://g.recordit.co/nGbuc5gxjH.gif)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
Sources: 
https://javascript.plainenglish.io/how-to-generate-an-array-of-random-numbers-in-javascript-f883de667e84
https://dirask.com/posts/JavaScript-generate-array-with-10-random-numbers-paolg1
https://www.w3schools.com/cssref/css_colors.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
A couple of challenges I had was writing the conditional statements for the game logic and debugging my random pattern function. When I tested my game with the array that was given in the instruction it was skipping blocks in the sequence. So I compared my nested if statements with the one in the instructions and I realized that I had put one of my conditions in the wrong order so it wasn't reaching the condition I need it to since a previous condition was already being met. Once I corrected the order of my conditional statements I got the game to function properly. From the beginning of this project, I knew that I wanted to create a randomly generated array rather than a given array to make for a better game experience. However, I don't really have any prior experience in javascript. So I went online to find documentation for pushing ints to an array to write a function. But I forgot to add a return statement and because of that, it did not work. The code wasn't storing the random array I had generated. I used console.log to see if the creating an array of length 8 and with integers 1 to 4. After some testing, I realized that it was only selecting 1, 2, & 3. What I realized is that multiplying the floor by 3 was only creating a range of 3 numbers. This is because I conflated that indexes start with 0 while the cardinality of a list starts with a 1.  After changing the 3 to a 4, my function was working properly.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I want to learn how to make websites using more modern programs. While HTML, CSS, and javascript are a good place to start, most websites written in HTML look like it was made in the early 2000s. I want to know how I make my game look like it was made in 2022. My main goal was to make a functional game, but it looks a bit like I made it in 2011. While functionality should always be a top priority of a web developer, UI/UX should also be up there on the priority list as users don’t want to use websites that are in desperate need of a refresh. How does someone find the right balance of functionality and aesthetics? Although, aesthetically speaking, web development is subjective so there may not be an exact answer. With that being said, most people can determine a poorly designed website that doesn’t work or is unreadable due to the color scheme. But what makes the difference between a just fine site and a magnificent one? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had more time for this programming task, I would have added more buttons and added more tones to be able to have a whole octave plus all 7 sharps. I also would have created a list of arrays that would play familiar songs. I would have given players the option to play a random 8 pattern or play the song game. Although, since the songs would be more familiar to users, I would make the buttons randomly switch places to keep them on their toes. When it comes to game design, you need to walk the fine line of games not being too easy but also not so complicated that they quit out of frustration. I believe that the switching notes for the song game are just complicated enough to keep users going. I would also work on the website aesthetically. I would modernize the website to fit the relaxed nostalgic vibes the game has. 



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
