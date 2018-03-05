# Aether

This project is a simpler take on [Patatap](https://patatap.com/) by Jono Brandel. I built this project as part of a code-along in Colt Steele's Web Developer Bootcamp course.

Using an HTML canvas, it draws upon JavaScript libraries to create animation and sound in response to user input.

## Core Features

The user can click any letter key on the keyboard to simultaneously trigger a sound and an animation.

The animation consists of different coloured circles appearing in randomly generated positions on screen, that scale down and disappear.

## Technologies

The JavaScript library [Howler.js](https://howlerjs.com/) is used to trigger the audio samples using built-in functions.

[Paper.js](http://paperjs.org/) is used to build the circle animations.

Both Howler and Paper are combined in a script to trigger animation and sound using custom JavaScript functions on key events.
