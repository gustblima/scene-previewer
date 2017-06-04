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
### Example:
#### Input Video
<a href="http://www.youtube.com/watch?feature=player_embedded&v=gRKKvzuOQEs
" target="_blank"><img src="http://img.youtube.com/vi/gRKKvzuOQEs/0.jpg"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

#### Output
##### (threshold=0.2, duration=0.3, mode=simple)
<img src="https://github.com/gustblima/scenes-previewer/raw/master/example/amazingnature_simple_0.20.gif" />

##### (threshold=0.35, duration=0.3, mode=mse)
<img src="https://github.com/gustblima/scenes-previewer/raw/master/example/amazingnature_mse_0.35.gif" />

***


##### Made by Gustavo de Biasi Lima.
##### Just for study.