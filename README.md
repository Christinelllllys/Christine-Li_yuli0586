# Christine-Li_yuli0586
Creative coding major project_Individual Task_

## *(Rhythm of Fear)*

#### ** Name: Christine Li (Yuanshan Li) **
#### ** Unikey: yuli0586 **

## 1. How to interact with the work
After the page loads you will see four yellow buttons at the top: **Level 1 / Level 2 / Level 3 / Level 4**. 
Click any button, wait a second, and the matching fragment of *Vivaldi – The Four Seasons: Winter* will loop. While the music plays, the background erupts into an audio-reactive animation whose intensity grows from Level 1 to Level 4. You can switch levels at any moment; the previous track stops instantly and its visual layer is replaced. The screaming character always stays in front so the focus is clear.

## 2. My individual approach to animating the group code
I chose **audio** (p5.FFT) to drive every motion. My responsibility inside the group was the large *lake & land* layer, but early tests that animated only that region felt too subtle. I therefore expanded the visualiser so it now fills the entire background, leaving the main character unmoved in front. Each level is realised with a distinct algorithm that mirrors a rising panic curve:

* **Level 1** – a single sine line with breathing dots: ordered thoughts just starting to quiver.
* **Level 2** – the line disintegrates into tidy dot columns that wobble faster when the music gets louder.
* **Level 3** – thousands of drifting particles flash in two colour layers, suggesting fractured thinking.
* **Level 4** – every grid cell spins and flips between circle and rounded square, a visual “meltdown”.

This full-screen, strongly audio-centric approach is different from my team-mates’ approaches.

## 3. Inspirations and their influence
Two classic visual elements shaped the design:
### (a) Tangled-scribble diagram – “inner noise”

![Girl surrounded by messy lines](./messymind.png)

The first reference (the girl hiding her face, encircled by messy doodles) expresses *cognitive overload* rather than outright panic. Those spaghetti-lines are thin, continuous, and still loosely organised; they look like hurried thoughts looping in place.

* **Level 1** therefore keeps a *single continuous sine wave* that rolls calmly across the screen. Dots grow and shrink along the line to hint at rising tension, mirroring the tiny chat bubbles in the picture.
* **Level 2** preserves the vertical rhythm of the scribbles but breaks the line into *neat dot columns*. This echoes the moment when thoughts “splinter” yet still obey an underlying beat. The columns sway sideways following two sine phases—like the illustration’s lines, which bend but do not explode.


### (b) Pop-art shock panel – “external blast”  

![Comic–style panic explosion](./panic.png)

The second inspiration image shows a man in a classic comic-book *jump scare*: an explosion effect behind him, red halftone dots everywhere. It screams sudden, public, uncontrollable fear. I extracted two components:  

1. **Radial explosion** -> everything must spin or radiate from screen-centre.  
2. **Dense halftone dots** -> small units should multiply until the picture feels crowded.  

* **Level 3** scatters *thousands of particles* that flash in two alternating palettes (foreground/background) to recreate the vibrating dotted texture. The dots drift but are confined to a flow-field—order hanging by a thread.  
* **Level 4** aims for the absolute burst: each grid cell continuously rotates and morphs between *circle* and *rounded square*. The square is a “broken” circle, a blunt metaphor for thought patterns shattering. Random palette picks and size-twitches mimic the posterised colours of pop art, while global rotation references the explosion’s spinning energy.  

