### NOTE: This project has been superseded by https://github.com/adamjmurray/ableton-midi-sculptor.
That project is basically the "2.0" version of this one. No further development of this project will occur.

# Ableton MIDI Clip Variator

The **Ableton MIDI Clip Variator**
is a [Max for Live device](http://ableton.com/maxforlive)
for [Ableton Live](http://ableton.com/live/)
that makes it easy to create variations of MIDI clips with tools to modify velocity and timing.

![Image of MIDI Clip Variator in use](./midi-clip-variator-in-use.gif)



## Installation and Usage

1. [Download](https://github.com/adamjmurray/ableton-midi-clip-variator/archive/master.zip) and unzip in the location of your choice
2. Drag the midi-clip-variator.amxd device into any MIDI track
3. Click the help button for usage instructions


## Features

* Shift the average velocity, start time, and duration of notes.
* Spread the velocity, start time, and duration of notes towards or away from the average value.
* Randomize the velocity, start time, and duration of notes with an intuitive 2-dimensional randomization control.
* Choose a range for the max change in value
* Controls are in a floating window that stays on top of Ableton Live, so you can quickly jump between different clips.


## Changelog

* Version 1.1
    * Added range parameter to control the maximum change in value
    * When editing, automatically show the clip's detail view
    * Display "Select a MIDI clip" whenever a MIDI clip is not selected
* Version 1.0
    * Edit MIDI clip's velocity, start (note start time), and duration using shift, spread, and random operations


## About

Designed and developed by [Adam Murray](https://github.com/adamjmurray).

Released under a [permissive free software license](https://github.com/adamjmurray/ableton-midi-clip-variator/blob/master/LICENSE.txt)

Built with [Max](http://cycling74.com/products/max/) and JavaScript.

Inspired by the [histogram features in Bitwig Studio](http://bitwig.com/bitwig-studio).


