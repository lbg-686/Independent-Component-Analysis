# Independent-Component-Analysis-Lab
In this notebook, we'll use Independent Component Analysis to retrieve original signals from three observations each of which contains a different mix of the original signals. This is the same problem explained in the ICA video.

# Dataset
Let's begin by looking at the dataset we have. We have three WAVE files, each of which is a mix, as we've mentioned. If you haven't worked with audio files in python before, that's okay, they basically boil down to being lists of floats.

Let's begin by loading our first audio file, [ICA mix 1.wav](ICA mix 1.wav) [click to listen to the file]:

# 用到的python库
numpy
wave
sklearn
matplotlib
scipy