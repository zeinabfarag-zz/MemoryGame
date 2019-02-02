# MemoryGame

## Overview

This is a memory game built using React. The application's UI is split into four components.

## Description

This app renders 12 different car images to the screen. Each image listens for click events. It keeps track of the user's score. The user's score is then incremented when clicking an image for the first time. The user's score is reset to 0 if they click the same image more than once. Every time an image is clicked, the images rendered to the page shuffle themselves in a random order. Once the user's score is reset after an incorrect guess, the game restarts.

## Installation

To run the application locally, first clone the repository:

	git clone https://github.com/zeinabfarag/MemoryGame.git
	cd MemoryGame
Then, install the depencies and start the app:
	yarn install
	yarn start
	
Now, open the local application on port 3000 at the URL: `http://localhost:3000/`.

## Technologies used

* React
* ES6
* Bootstrap
* CSS

## Website

https://zeinabfarag.github.io/MemoryGame/
