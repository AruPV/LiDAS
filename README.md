# A Digital Audio Synthesizer Written in C++ for Linux

## What is this

An audio synthesizer for linux systems.

## How to run

1. Download the project and compile using make.
2. Run output file from terminal appending |aplay at the end of the call

## Roadmap

- [] Complete 8-bit synthesis of c5
	- [] 8-bit Sine
	- [] 8-bit sawtooth
	- [] 8-bit triangle
	- [] Change wave during runtime
- [] Finish this README (lol).
- [] Pitch change
	- [] Allow for pitch to be chosen before compilation.
	- [] Allow for pitch to be changed during runtime.
		- [] Pitch modulation
		- [] Fixed pitch at 12 equal temperaments
- [] Play on your keyboard mode
	- [] Allow for holding of a key to determine whether or not a note plays
	- [] Add option to map different pitches to keys close to a piano layout
- [] Polyphony
	- [] Can pick multiple notes to be played at once
	- [] Piano mode can recognize multiple notes at once
- [] LFOs
