## DOCUMENTATION

- Click [JUCE](https://juce.com/learn/documentation/).

## RESOURCES

- [Getting Started with JUCE](https://www.youtube.com/watch?v=JHTcLVOcnQ4&t=1410s) - Setup with [Projucer](https://docs.juce.com/master/tutorial_new_projucer_project.html) on Windows. (Important!)
[Download JUCE](https://juce.com/get-juce/) Unpack the JUCE folder and place it in the folder where your plugin folder is located.
  
- [Getting Started with Cmake](https://www.youtube.com/watch?v=Uq7Hwt18s3s&t=198s) for Windows.
To use CMake to build the examples and extras bundled with JUCE, simply clone JUCE and then run the following commands, replacing "DemoRunner" with the name of the target you wish to build.
  
```
cd /path/to/JUCE
cmake . -B cmake-build -DJUCE_BUILD_EXAMPLES=ON -DJUCE_BUILD_EXTRAS=ON
cmake --build cmake-build --target DemoRunner
```

- [100 videos of JUCE](https://www.youtube.com/watch?v=7n16Yw51xkI&list=PLLgJJsrdwhPxa6-02-CeHW8ocwSwl2jnu) on JUCE Framework, includes almost all the basic functionality for plugin. (Best used for implementation)
- [Demo EQ plugin]([https://www.youtube.com/watch?v=i_Iq4_Kd7Rc&t=3906s](https://www.youtube.com/watch?v=ZKmFZpJEZ3k)) The Demo commit is based on this video by @MatkatMusic
- [Theory](https://www.youtube.com/@akashmurthy/playlists) - Youtube playlist for DSP and audio programming. (GOD LEVEL Explanation)  

## Overview
![plugin_f](https://github.com/lagooneration/AudioPlugin_EQ/assets/142176950/a4cabb4d-4d2d-45ac-ba41-aa868ff407ef)

## Goals
- Getting familiar with the JUCE framework
- Getting familiar with EQ and filter design
- Creating a spectrum analyser for one audio
- Creating a stand alone plugin to drag and drop play two audios and display the frequency spectrum individually
- Finding a way to incorporate both audios to display on a single display (with a differentiating parameter like color)
- POC

## Desired Input/Output:
Arpeggiator
[arp.webm](https://github.com/lagooneration/AudioPlugin_EQ/assets/142176950/052508c0-d88c-4062-91f9-1f93bf712027)
![arp](https://github.com/lagooneration/AudioPlugin_EQ/assets/142176950/941862a9-f043-4a8e-a339-ce4be806e70d)
Bass
[bass.webm](https://github.com/lagooneration/AudioPlugin_EQ/assets/142176950/7a749e6d-4fb8-47bc-84e3-95808ddf4d5f)
![bass](https://github.com/lagooneration/AudioPlugin_EQ/assets/142176950/a343f599-ce83-4289-bd2f-398f10b98f75)

- Result
Supposed to be distinguishable
![combined](https://github.com/lagooneration/AudioPlugin_EQ/assets/142176950/b2d11f31-6fab-40f0-961e-02f67cf8cf63)


  ## Remarks
