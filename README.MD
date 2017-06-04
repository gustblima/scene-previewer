# Video Scene Previewer Generator

This code uses OpenCV, numpy and imageIO

## Parameters
1. Input file --file => video.mp4
2. Mode --mode => simple
3. Threshold --threshold => 0.2
4. Gif Scene Duration  --duration => 0.5

---

### Modes:
##### Simple and Mean Squared Error
##### simple:
Just compare the pixels sum change in the current frame with the previous frame
##### mse:
Mean Squared Error

### Threshold:
How much change in the video is considered a scene change. Best values falls between 0.2~0.3

***

##### Made by Gustavo de Biasi Lima.
##### Just for Study.