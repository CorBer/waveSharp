# waveSharp 002_3 DEMO application (2022-dec-25)

## update on 2022-12-25

We have started testing the initial setup to allow batch processing of images, this is still only PNG and TIFF based. All settings you can currently alter in waveSharp are available during batch processing.

The batch-processing can be used to either:
1) create a set of sharpened/colour-balanced files for later use (in the same format as the original)
2) create a GIF (by default restricted to a maximum of 255 different colours )
3) create an APNG (animated PNG that allows lossless imagequality-compression and full colour animation (8bit/channel), makes the results 2-3times the size of a GIF)

All this functionality is allready working in our testversion but several things need a bit more tweaking and quality-control (WYSIWYG) before sharing.

## update on 2022-12-21
An updated version for windows is available that solves the issues with saving to TIFF and issues with the interface due to scaling (**waveSharp_WIN64_20221221.zip**)

see: https://github.com/CorBer/waveSharp/releases/download/v002_3/waveSharp_WIN64__20221221.zip

## update on 2022-12-20
The windows version has been updated since saving to TIFF was not possible.

## released on 2022-12-19
This repository holds the first public release (freeware) of the waveSharp project.  The aim of this project is to recreate the RegiStax6(RS6) wavelet sharpening module.  RS6 was developed in 2011 only for windows 32bit computers, waveSharp is developed for 64bit computers and multiple operating systems. Therefore this application is only meant to sharpen/enhance images that have been created using other software (alignment/stacking). 

The development of waveSharp was done in close collaboration with:
- Grant Blair
- Michael Owen
- Filip Szczerek
- Cheng-Yang Tan

I want to thank them first of all for helping me get started and spending part of their free time on this. They have tested many (over 50) earlier versions of the application and provided both help/bugs and ideas that helped me steering this project. 

Cor Berrevoets 

![](images/Screenshot%20at%202022-12-17%2009-03-24.png?raw=true)
![](images/Screenshot%20at%202022-12-17%2009-31-35.png?raw=true)

