
# JPLab - Change Log

## v2.1.1
* Ties now correctly honor the gate length and swing values (All sequencers)
* Ties now work correctly with the Phase Clock setting (All Sequencers)
* Helm now correctly quantizes notes. Previously was quantizing to notes not selected in the note pool. (Evo Seq) https://github.com/patheros/JPManuals/issues/12
* The "Quantize" Inversion Mode now correctly works. Previously was quantizing to notes note selected in the note pool. (https://github.com/patheros/JPManuals/issues/11
* VCV no longer crashes when you save a preset with an attached Helm. https://github.com/patheros/JPManuals/issues/14

## v2.1
* EvoSeq - New Sequencer Module! 
  * Gives you triggers to apply random evolutions to the sequence.
* Octavator - New Utility Module!
  * Random, seeded, modifications to the Octave value of a V/Oct sequence.
* ThreeTrack Chord mode now shows correctly in the right click menu. https://github.com/patheros/JPManuals/issues/9
* Randomize CV now creates a random note pool if the note pool is empty.
* Shift & Shuffle expander's `In Sequence` mode now works on Star Matrix Jr.
* Added ability to select root note when initalizing the note pool to a scale.
* Tweaked JrImprove's formula for adding notes when notes are added to its note pool.

## v2.0.2
* Shift Up and Down input ports had their labels swapped. That is now fixed.


