# waveSharp development in the final stages (2024 11 15)
Since august we have been working on a new version of waveSharp based on python-libraries


# waveSharp development tests with Python (2024 08 16)
The code for waveSharp is written in Pascal/Lazarus and although thats a "compiled" language
it seems that its not the fastest for certain tasks we do. During the development of the denoising
routine we found that it is slow and limited (up to 4096x4096px images). Currently we are testing a
new way to run waveSharp using Python code. This allows us to use fast and speed-optimized calculation routines
Python has available from several libraries. More info will be shared at https://github.com/CorBer/waveSharp/discussions/65

# please report issues (2024 04 15)
Although several thousand people have downloaded the freeware only a few have submitted 
issues/discussions. <br>
report your issues using https://github.com/CorBer/waveSharp/issues as they will be used for
further development. If you have very specific ideas/request please describe those in detail
when reporting.


# waveSharp 1.0 beta released (2023-12-09)
On the 9th of december 2023 we have released the 1st beta-version of waveSharp 1.0 
Further information available at https://github.com/CorBer/waveSharp/releases/tag/v1.0beta <br>

![waveSharp 1.0 team](/../main/images/wavesharpv1_0beta.png)

# waveSharp 0.2 prototype released (2023-01-31)
Available at https://github.com/CorBer/waveSharp/releases/tag/v0_2 <br>


# made by
The development of the 0.2 release of waveSharp was done by Cor Berrevoets 
in close collaboration with:

- Grant Blair
- Michael Owen
- Filip Szczerek
- Cheng-Yang Tan
- Don Capone

I want to thank them first of all for helping me get started and spending part of their free time on this. They have tested many earlier versions of the application and provided both help/bugs and ideas that helped me steering this project.  

This update has the following additional features
- user set processing area  
- cropped image saving
- resized image saving
- image edge padding/trimming 
- alignment of RGB channels (at subpixel level)
- new sharpening method (bilateral filter)
- automatic version checking

Cor Berrevoets 


