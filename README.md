# IMGD5010_FinalProject
A final project to demonstrate a synthesis of materials explored in the course. 

## Approaching the Hall of the Mountain King
### link to work

(https://editor.p5js.org/hinaccurate/full/tL1dzzvhu)[https://editor.p5js.org/hinaccurate/full/tL1dzzvhu]

### what I tried to create 

An animation set to Edvard Grieg's "In the Hall of the Mountain King," showing the character Peer Gynt, from the Ibsen play of the same name, journeying to and into the troll king's firey lair.

The animation starts with a wide, empty blue sky. As the orchestra quietly begins to play, a small grey figure (Peer Gynt) appears over the horizon. From his point of view at the bottom center of the animation, it appears that Peer Gynt is walking steadily toward a mountain in the far distance, the size of which only becomes apparent as it looms larger and larger over him. At its base, the entrance of a cave appears, it too only becoming larger as Peer Gynt makes his steady way forward. He enters the cave and is engulfed in darkness, but continues onward until a distant, firey light begins to show his way again. The light continues to brighten as he goes deeper into the cave--and if that wasn't proof enough that he was entering some unnatural domain, the cave starts to slowly appear more constructed and intentional as rocks resolve into columns to either side of Peer Gynt's path. 

### what's actually there

...at which point, the animation pauses and a black rectangle appears in the corner with the timestamp in milliseconds, running through to the end of the music.

The animation itself was created using only circles, but variety and different effects are made possible by changing their size, color, and locations. In addition, using the blur filter and layering circles within individual called functions allowed for the simulation of perspective, shadows, and highlights. The timing of the animation is intended to match the music, and is controlled using milliseconds (more accurate and easier to match to the music than framerate if there's a concern with lag).

### what didn't really work...

While originally the intention was to animate the entire 2 minutes and 30 seconds of the piece, the project currently stands at having only a little over a minute of the animation complete. Unlike other works submitted, the issue with completion is not one of broken or nonworking code, but rather:

1. the time needed to create enough individual function "animation cells" to complete the full narrative of the piece (which did lead to the creation of a second p5 file that used a keyPressed function to "flip" between two functions, which helped smooth the transition between them without having to rerun the entire animation to review incremental changes)
2. and perhaps more significantly, the time needed to find and record the increases in the music's tempo that the animation needed to match. Orchestral versions of "In the Hall of the Mountain King" don't exactly match the sheet music, so I quickly determined (after probably about 6 measures) that just using what should be the _mathematical_ number of milliseconds to time the animations would very quickly lead to a mismatch with the _played_ number of milliseconds.

I largely did these tempo changes by ear for the first minute of the animation, but as the tempo increased and I anticipated needing to plan for more significant changes to Peer Gynt's animation, each arriving more quickly, I realized I needed to be able to actually storyboard the remainder of the piece using real timestamps (leading to the creation of the box that showed the runtime while the music played, so I could manually record the millisecond goalposts).

### future

While I'm interested in maintaining the "animation cell" style of individual functions, future work on this project will definitely need some better way to capture the timestamps necessary to match the action to the music. Once a complete runthrough of the animation is available, I think I'd also go back and make some Adjustments to the content of the cells themselves just in terms of appearance (as I have come to find the appearance and color of the mountain in the first minute less than ideal...). And, finally, it would probably be interesting to figure out how to maintain the cell style without the significant _length_ of the code it requires at present.

