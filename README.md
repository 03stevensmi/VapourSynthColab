# VapourSynthColab

A Google Colab notebook set up for both conventional and machine learning-based video processing. Run ESRGAN or MXNet models, OpenCL and CUDA filters, and CPU filters on video frames simultaneously in VapourSynth scripts, or use VapourSynth filters to pre/post process videos for other ML Colab projects, and do it all in the cloud for free. 

[UPDATED]:
I have fixed this colab and updated the links. I have not tested this as of yet but there should be no issues.

![Colab1.png](https://raw.githubusercontent.com/AlphaAtlas/VSSH-Wiki-Images/master/images/Colab1.PNG)
![Colab2.png](https://raw.githubusercontent.com/AlphaAtlas/VSSH-Wiki-Images/master/images/Colab2.PNG)

Basic usage:
* Log in to Google, open the notebook: https://colab.research.google.com/github/03stevensmi/VapourSynthColab/blob/master/VapourSynthColab.ipynb
* Run the "Check GPU".
* After "Check GPU", Make sure to first run the 3 new cells before setup. (THIS IS IMPORTANT).
* Now run the "Setup" cells.
* Run the cell with the example VapourSynth script, or load your own video and edit it.
* Run the "Preview Options" cell to test the script.
* Generate the preview in the preview cell. 
* Process the whole video in a scratch cell. 

For basics on VapourSynth and super resolution filters, see the wiki (and links to other guides) here:
* http://www.vapoursynth.com/doc/
* https://github.com/AlphaAtlas/VapourSynth-Super-Resolution-Helper/wiki/VapourSynth-Basics

Browse through VS plugins and scripts here, search for "vapoursynth" on github, or look through the "VapourSynthImports" folder and VapourSynth's imported plugins:
* http://vsdb.top/

I highly recommend stabilizing ESRGAN output with a temporal filter, or using a dedicated video model from another repo. Also, keep in mind that Colab's CPU is very slow, and that sessions are limited to 12 hours, so use GPU accelerated filters wherever possible in scripts with heavy CPU filters, and write your processesed videos to Google Drive or Nextcloud.

Grab models for specific kinds of content here, or train your own:
* https://upscale.wiki/wiki/Model_Database
* https://colab.research.google.com/drive/1ygwTH7nN66UEUjD87u8kdFAGoVBzL-Bt

For help, just post an issue, or ask in the Game Upscale or Animation Upscale Discords.
* https://discord.gg/cpAUpDK
* https://discord.gg/sGH8kKc
