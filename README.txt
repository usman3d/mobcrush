mobcrush
========

Mobcrush library


This is a project that will build the Mobcrush library against the underlying VideoCore library that it is built upon.

Any bugfixes will be made in the VideoCore project.


The Mobcrush graph looks like this:


GLES Source(Mobcrush)---->
Camera Source(VideoCore)-> Video Mixer (VideoCore) -> H264 Encoder(VideoCore) -> RTMP Packetizer(VideoCore) -> RTMP Output (VideoCore)

CoreAudio Source (Mobcrush)->
Mic Source (VideoCore) -----> Audio Mixer (VideoCore) -> AAC Encoder (VideoCore) -> RTMP Packeizer(VideoCore) -> RTMP Output (VideoCore)
