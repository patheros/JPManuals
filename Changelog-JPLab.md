
# JPLab - Change Log

## v2.1.1
* Ties now correctly honor the gate length and swing values (All sequencers)
* Ties now work correctly with the Phase Clock setting (All Sequencers)
* Helm now correctly quantizes notes. Previously was quantizing to notes not selected in the note pool. (Counter Point) https://github.com/patheros/JPManuals/issues/12
* The "Quantize" Inversion Mode now correctly works. Previously was quantizing to notes note selected in the note pool. (https://github.com/patheros/JPManuals/issues/11
* VCV no longer crashes when you save a preset with an attached Helm. https://github.com/patheros/JPManuals/issues/14

## v2.1
* FourTrack's CV input now works. https://github.com/patheros/JPManuals/issues/5
* Randomize CV now creates a random note pool if the note pool is empty.
* Fixed Navigator's clock inputs being backwards. https://github.com/patheros/JPManuals/issues/10
* Added Exponential Ramp option to Navigator.
* Shift & Shuffle expander's `In Sequence` mode now works on Star Matrix.
* Added ability to select root note when initalizing the note pool to a scale.
* Tweaked Improve's formula for adding notes when notes are added to its note pool.

## v2.0.2
* Navigator now has a Ramp setting that controls how CV2 changes from step to step.
* Fixed bug where Four Track was crashing with a high thread count.
* Removed duplicated L-Var setting on Improv. https://github.com/patheros/JPManuals/issues/1
* Removed all DEBUG statements to improve performance https://github.com/patheros/JPManuals/issues/4

## v2.0.1
* Fixing Four Track crashing when added to a patch. See issue https://github.com/patheros/JPManuals/issues/2

