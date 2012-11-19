PerceptualP5 
------------
<b>Processing Sketches from the Perceptual Computing Lab<br>
Download the [Perceptual Computing SDK](http://software.intel.com/en-us/vcsource/tools/perceptual-computing-sdk)<br/>
Download [processing](http://processing.org)</b>

* <b>ImageViewer</b> - Displays the different types of image data available (label, RGB, depth, IR), for processing 1.5.1 and 2.beta6 ([Chris](http://twitter.com/_ChrisRojas_))
  * Mouse movement sets depth and ir visibility
* <b>HandVisualizer</b> - Basic hand and fingertip tracking, for processing 1.5.1 and 2.beta6 ([Chris](http://twitter.com/_ChrisRojas_))
* <b>FingerTips</b> - Basic fingertip tracking, for processing 1.5.1 and 2.beta6 ([Chris](http://twitter.com/_ChrisRojas_))
* <b>HandViz</b> - Hand position and openness tracking/visualizer, for processing 1.5.1 and processing 2.beta6 ([Seth](http://twitter.com/djTomServo))
* <b>FingerFluid</b> - Fingertip tracking and fluid, for processing 1.5.1  ([Seth](http://twitter.com/djTomServo))
  * requires [diewald_fluid](http://thomasdiewald.com/blog/?p=95)
  * requires [GLGraphics](http://glgraphics.sourceforge.net/)
  * Notes: press 'l' to toggle label map background display.  The "fluid curtain" effect needs some work,<br/>if someone wants to fix it up, please do!  Code starts at 'if(curtain)' in the draw() method.
* <b>PXCBlobs</b> - Label map based blob detection, for processing 1.5.1 and 2.beta6 ([Seth](http://twitter.com/djTomServo))
  * requires [v3ga Blob Detection](http://www.v3ga.net/processing/BlobDetection/)
* <b>PXCPhysicsBox</b> - Blob detection and physics interaction, based on Amnon Owed's [Kinect Physics for Processing Tutorial](http://www.creativeapplications.net/processing/kinect-physics-tutorial-for-processing/), for processing 1.5.1 and 2.beta6 ([Seth](http://twitter.com/djTomServo))
  * requires [v3ga Blob Detection](http://www.v3ga.net/processing/BlobDetection/)
  * requires [fisica](http://www.ricardmarxer.com/fisica/)
  * Notes: Needs better polygon creation routines, any takers?
