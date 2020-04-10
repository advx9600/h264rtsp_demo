# 项目是 h264rtsp

## What it does
手机作为视频服务器，可以被其它设备接收<br/>
clone from https://github.com/fyhertz/libstreaming and https://github.com/bytestar/android-h264-stream-demo

## How does it work 
The working flow as below
```
camera preview data(YV12) -> YUV420sp -> MediaCodec -> H.264 data
```
### VLC
```
vlc  rtsp://ip:port   example rtsp://192.168.1.100:1234
```
