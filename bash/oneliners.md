# Variable bitrate conversion to webm:
```bash
ffmpeg -i input.mp4 -c:v libvpx -b:v 1M -c:a libvorbis output.webm
```
