ffmpeg的使用和安装
===
## 1.去ffmpeg的官网下载地址:https://ffmpeg.zeranoe.com/builds/ 点击"download build"按钮，下载zip文件。
## 2.解压

# 环境变量的配置
## 1、将下载的ffmpeg解压到指定目录下，如在：G:\目录下；
## 2、右击此电脑——>属性——>高级系统设置——>环境变量。在系统变量的path变量里添加解压的路径。
例如：G:\ffmpeg-4.0-win64-static\ffmpeg-4.0-win64-static\bin
## 3、配置完成后运行cmd，输入ffmpeg，若显示如下界面，则说明配置成功。

ffmpeg version git-2019-12-06-b66a800 Copyright (c) 2000-2019 the FFmpeg developers
  built with gcc 9.2.1 (GCC) 20191125
  configuration: --enable-gpl --enable-version3 --enable-sdl2 --enable-fontconfig --enable-gnutls --enable-iconv --enable-libass --enable-libdav1d --enable-libbluray --enable-libfreetype --enable-libmp3lame --enable-libopencore-amrnb --enable-libopencore-amrwb --enable-libopenjpeg --enable-libopus --enable-libshine --enable-libsnappy --enable-libsoxr --enable-libtheora --enable-libtwolame --enable-libvpx --enable-libwavpack --enable-libwebp --enable-libx264 --enable-libx265 --enable-libxml2 --enable-libzimg --enable-lzma --enable-zlib --enable-gmp --enable-libvidstab --enable-libvorbis --enable-libvo-amrwbenc --enable-libmysofa --enable-libspeex --enable-libxvid --enable-libaom --enable-libmfx --enable-ffnvcodec --enable-cuvid --enable-d3d11va --enable-nvenc --enable-nvdec --enable-dxva2 --enable-avisynth --enable-libopenmpt --enable-amf
  libavutil      56. 36.101 / 56. 36.101
  libavcodec     58. 64.101 / 58. 64.101
  libavformat    58. 35.101 / 58. 35.101
  libavdevice    58.  9.101 / 58.  9.101
  libavfilter     7. 67.100 /  7. 67.100
  libswscale      5.  6.100 /  5.  6.100
  libswresample   3.  6.100 /  3.  6.100
  libpostproc    55.  6.100 / 55.  6.100
Hyper fast Audio and Video encoder
usage: ffmpeg [options] [[infile options] -i infile]... {[outfile options] outfile}...

Use -h to get full help or, even better, run 'man ffmpeg'
