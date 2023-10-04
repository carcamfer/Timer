# SVG Timer Application

## Overview

A simple timer application that visually depicts the countdown using an SVG circle. It allows users to start, pause, and see the visual representation of a timer countdown on a user-friendly interface.

## How It Works 

### User Interaction:

1. The user inputs a desired time duration.
2. Clicks "Start" to begin the countdown.
3. Can click "Pause" to pause the countdown at any moment.

### Visual Representation:

- An SVG circle gradually 'unwraps' as the timer counts down, providing a visual indication of the remaining time.
  
## Technologies Used 

- HTML5
- CSS3
- JavaScript

## Key Files Description 

### index.html 

Comprises basic structure and elements like SVG circle and buttons for user interaction. Contains:
- SVG Circle: Visually represents the timer countdown.
- Input: For user to define the timer duration.
- Buttons: To "Start" and "Pause" the timer.

### index.js 

Manipulates the SVG circle's stroke offset and interacts with an instance of the Timer class:
- Fetches and utilizes DOM elements.
- Instantiates and manages the `Timer` instance with callbacks.

### timer.js 

Defines the `Timer` class that handles the timer logic:
- Manages the timer's state (start, pause).
- Invokes optional callback functions during timer events (start, tick, complete).

## Usage 

- Define the timer's duration.
- Start or pause the timer.
- Watch the visual countdown.

## Contributing 

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.



