This code was used to generate the results in Vroomans RMA, Hogeweg P, Ten Tusscher KHWJ. 2018. Around the clock: gradient shape and noise impact the evolution of oscillatory segmentation dynamics.. EvoDevo 9:24

The code depends on the following libraries: libpng-dev and zlib1g-dev.
It was developed in 2014, so the makefile may be a bit old-fashioned.

After installing dependencies, simply type "make"; the binary will be placed in bin/
The second makefile, specifying flags and libraries, can be found in obj/
It contains a few flags that can be specified to compile different versions: the main simulation code and different programs to analyse simulation outcomes.

The notebook.zim file is a wiki with more detail about the structure of the code and all its functions.
