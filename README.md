# Wordle en español
Wordle, but for my sexy linguist girlfriend <3

<img width="400" alt="wordle-espanol" src="https://user-images.githubusercontent.com/96708796/165432122-272aabdd-2c4c-48c0-af6a-9f0705d1ac24.png">

## Table of contents
* [Features](#features)
* [What I Learned](#what-i-learned)
* [Technologies](#technologies)
* [Special Thanks](#special-thanks)

## Features
* New word every refresh!
* Classic Wordle appearence and colors
* Full keyboard featuring accented characters
* Custom alert messages
* Dynamic animations for invalid and correct guesses

### Future Features
* Improve mobile compatibility (depends if hope actually wants to play this)
* Store player data in local storage

## What I Learned
* `focus()`,`ref={}`, and `onKeyDown={}` can be used to get keyboard input from player
*  `e.key` is more straightforward than charcodes
* `async` and `await` can be used to wait for `Promises` of API data to resolve
*  Reference classes and `querySelectorAll()` can be used to add CSS animation classes
*  `tabIndex={0}` can be used to allow non-input elements to be focused by the keyboard
*  `map()` can be used twice for nested arrays
*  Specific percentages can be used within `@keyframes` to create animations that reset
	
## Technologies
Project is created with:
* React
* JavaScript (ES6)
* HTML 5
* CSS 3
	
## Special Thanks
* Large up Datamuse for da spanish words
* [Link to API Documentation](https://www.datamuse.com/api/)
