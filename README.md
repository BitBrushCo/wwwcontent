# www.BitBrush.co
## The Front End
This is the project to hold contents of www.BitBrush.co. This repository maybe merged with dynamic portion of www.bitbrush.co site in the future. For now it will only contain text content, images, animations, html, css, javascript and javascript libraries.

##Demo Link
https://bitbrushco.github.io/wwwcontent/


## Encoding Video
We may host our own video. If we choose to host then it is most likely that hls will be used.
How to encode portfolio video from mp4 to hls using ffmpeg.

Some sample ffmpeg command

```
ffmpeg -i DCL-Reel.mp4 -profile:v baseline -level 3.0 -s 1280x720 -start_number 0 -hls_time 10 -hls_list_size 0 -f hls index.m3u8
```
