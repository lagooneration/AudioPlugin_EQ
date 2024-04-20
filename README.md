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
