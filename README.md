# ![x](/../main/images/waveSharp3.ico) waveSharp3 released (2025 12 09)
![x](/../main/images/aboutws3.webp)<br>

We have released waveSharp 3 on the **9th of december 2025 09_00 local time (Netherlands)**.<br><br>
The past months the testing team has been using/testing a new version of waveSharp.<br> 
More information on this release is available from:<br> 
https://github.com/CorBer/waveSharp/releases

We also have the following documentation available:
- ![list of changes in WS3](https://github.com/CorBer/waveSharp/releases/download/v3.0/list_of_changes_20251208.pdf)
- ![installation guide for windows and linux](https://github.com/CorBer/waveSharp/releases/download/v3.0/WS3_InstallationGuide_20251208.pdf)

<br>
<br>

# ![x](/../main/images/waveSharp2.ico) waveSharp2 release available (2024 12 09)
Today one year has passed since we released waveSharp1. Information on how to download/install (windows and Linux) is available see https://github.com/CorBer/waveSharp/releases.  

**documentation**<br>
The ![GUI documentation](https://github.com/CorBer/waveSharp/releases/download/v2.0/waveSharp.v2.0.Documentation.pdf) 

The following HOW-To documents are available for download<br>
From Don:
- ![Animation](https://github.com/CorBer/waveSharp/releases/download/v2.0/HOW-To.Animation.pdf)
- ![Background enhancement](https://github.com/CorBer/waveSharp/releases/download/v2.0/How-To.BackgroundEnhance.pdf)
- ![De-Rind](https://github.com/CorBer/waveSharp/releases/download/v2.0/How-To.DeRIND.pdf)

From Grant:
- ![HistoGram](https://github.com/CorBer/waveSharp/releases/download/v2.0/How-To.HISTOGRAM.pdf)

From Mike:
- ![FFT_Denoise](https://github.com/CorBer/waveSharp/releases/download/v2.0/HowTo_Denoise.pdf)
- ![Processing Tabs](https://github.com/CorBer/waveSharp/releases/download/v2.0/HowToProcessingTabs.pdf)


The largest changes in this version :
  - python is used for most calculations
  - the default colour-model is OKlab (see https://bottosson.github.io/posts/oklab/)
  - RGB balance (in the histogram) can be used with a threshold 
  - Denoising has been improved (also works for larger images and is a lot faster) and is easier to use 
  - BackGround Enhance tool allows to brighten moons around planets without affecting the planet 
  - De-Rind Tool allows to soften the sometimes visible rind on the edge of planets
  - Disable Background tool allows inspecting the image in new ways
  - Batchprocessing allows images to be derotated/aligned based on a user choosen reference-image
  - Animations can use pause-sections (both after the forward and after the reverse)
  - Many GUI functions have been generalized 

<br><br>

# waveSharp2 development tools (2024 11 21)
WaveSharp was Built using only free tools. The sourcecode for all versions was build using the **Lazarus IDE** (https://www.lazarus-ide.org/) and using the **FreePascal** Compiler(https://www.freepascal.org/) these free and well designed tools have allowed me to create at the same time windows and linux versions. In the new V2 version we will also be using **Python** (https://www.python.org/) as a workhorse for more complex operations that would be either difficult to design in pascal or are too slow. To do this we needed a bridge between Lazarus/FreePascal and Python to allow fast/easy flow of data. The **Python4Delphi** (https://github.com/pyscripter/python4delphi) libraries/components have proven to allow all of this. Finally to make installing for new users as easy as possible we used **InnoSetup** (https://jrsoftware.org).
I want to thank all the developers involved in creating/providing all of the above (free) tools. 

# waveSharp2 final stage (2024 11 15)

Since august we have been working on a new version of waveSharp based on python-libraries. We are expecting
to release the next version early december. We have redesigned both the interface and functionality and this release
also comes with a set of completely new routines. You can for instance show dim moons around a planet without changing the planet
itself.

# waveSharp2 development with Python (2024 08 16)
The code for waveSharp is written in Pascal/Lazarus and although thats a "compiled" language
it seems that its not the fastest for certain tasks we do. During the development of last years denoising
routine we found that it is slow and limited (up to 4096x4096px images). Currently we are testing a
new way to run waveSharp using Python code. This allows us to use fast and speed-optimized calculation routines
Python has available from several libraries. 








# waveSharp 1.0 beta released (2023-12-09)
On the 9th of december 2023 we have released the 1st beta-version of waveSharp 1.0 
Further information available at https://github.com/CorBer/waveSharp/releases/tag/v1.0beta <br>





