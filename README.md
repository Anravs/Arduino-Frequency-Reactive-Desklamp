# Arduino-Frequency-Reactive-Desklamp

Frequency Reactive Desklamp for Arduino

A microphone listens to sound and the arduino breaks down the incoming signal into it's frequency analysis through the FHT.
Based on the frequencies present -> maps them to R/G/B colors on the [0 255] scale based on low/mid/high frequency ranges.

The coloring is shown in a cylidrical tube that changes amplitude of the color based on how loud the sound is.

Alternatively, there is another mode for coloring based solely on color intensity changes.
-> If a sound's value stays constant then color is green
-> If a sound's value goes up then color is yellow
-> If a sound's value goes down then color is purple
