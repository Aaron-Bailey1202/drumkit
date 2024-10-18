# Drum Kit Project

This is a simple **Drum Kit** web application that allows users to play different drum sounds by pressing the on-screen buttons or using specific keys on the keyboard.

## Features

- **Interactive Buttons**: Click on buttons to play different drum sounds.
- **Keyboard Integration**: Press keys (`w`, `a`, `s`, `d`, `j`, `k`, `l`) to trigger drum sounds.
- **Sound Effects**: Different drum sounds for each key (snare, toms, crash, kick).
- **Animations**: Visual feedback with button animations when keys are pressed.

## How It Works

The app detects both button clicks and keypresses. Each interaction triggers the corresponding drum sound and briefly animates the button to give visual feedback.

### Drum Sounds
- **w**: Snare drum
- **a**: Tom 1
- **s**: Tom 2
- **d**: Tom 3
- **j**: Tom 4
- **k**: Crash cymbal
- **l**: Kick bass

## Project Structure

- **index.html**: Contains the structure of the webpage with buttons corresponding to each drum sound.
- **styles.css**: Contains the styling for the buttons and animations.
- **index.js**: Handles the logic for detecting button clicks and key presses, playing sounds, and adding animations.
