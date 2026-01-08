# YET is your Eye Tracker

![YET Logo](https://github.com/schmettow/YET/raw/main/docs/logo/YET%20Logo%20small.PNG)

Your Eye Tracker is a low-budget eye tracking platform based on a cheap endoscope camera, 
3d printed parts and OpenCV image processing. It currently reaches around 2.5° error on average, with a minimum of 5°.
This is a little less accuracy as than what commercial eye trackers offer, at $1/1000$ the price. 
This makes Yet Zero particularly suited for educational purposes and many research applications.

**[Tutorial](https://schmettow.github.io/yet_zero/)**

YET can be assembled from scratch within minutes. Provided one first prints the socket.
The tutorial describes the assembly, installation and usage of YET. Yet comes ready to try, with
a pre-defined experiment. [Read more on the Uncanny Valley experiment](https://github.com/schmettow/Uncanny-Valley/blob/master/Uncanny%20Valley.docx)[Use download button]

**Built-in Data Science**

Yet Zero uses CSV tables to specify the experimental design, which can be 
edited using any table calculation program that exports to CSV, or any text editor.
Included is a full data analysis pipeline in tidy R, using the Quarto system.
Beginners can quickly produce research reports and learn the basics of eye tracking data analysis with Yet.


**Theory of Operation**

The inspiration for Yet came from an evolutionary point of view, more specifically the *cooperative eye hypothesis*.
Basically, the theory says that the human eye evolved into its modern appearance to make it easier for others to see where we are looking.
If the eyeball is such a strong signal, then building an eye tracking mechanism should be easy, right?
If you are interested, here is a deeper [discussion of the theory](https://github.com/schmettow/yet_biomim/blob/main/YET_CEHR.docx)[Use download button]

