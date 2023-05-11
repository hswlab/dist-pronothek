# Pronothek Video Downloader
[![GitHub](https://img.shields.io/github/license/hswlab/dist-pronothek)](https://github.com/hswlab/dist-pronothek/blob/main/LICENSE)
[![Downloads](https://img.shields.io/github/downloads/hswlab/dist-pronothek/total)](https://github.com/hswlab/dist-pronothek/releases/latest)
[![Downloads](https://img.shields.io/github/v/release/hswlab/dist-pronothek)](https://github.com/hswlab/dist-pronothek/releases/latest)

This app is an experiment of mine to convert a .NET6 MVC web application into a fully functional desktop application using Electron .NET. User ineractions like configuring storage folders or video editing are rather not common in a classic web application. This is where Electron's strengths come into focus, as it allows you to perform actions closer to the operating system. This app also serves as an experimental environment for me to learn how to use ffmpeg in C#. Currently I'm trying to understand how video streams are working and how you can fetch and convert such data. Maybe this experiment will at least develop into a useful video downloader for various streaming/media. In the current version 1.0.0, only video downloads from xvideos.de are supported, because during my familiarization with ffmpeg I mainly encountered code examples for this kind of media^^. It's really interesting and a bit funny for which kind of applications other developers like to sacrifice their development time. Quite often it has something to do with xxx media :D 
More download options will probably come gradually as I learn more about videostreams and ffmpeg.

![preview](https://github.com/hswlab/dist-pronothek/blob/main/Screenshot.png)

# Nuget packages and associated licenses used for the app
- Newtonsoft.Json <a href="https://licenses.nuget.org/MIT">`license`</a>
- Esprima <a href="https://licenses.nuget.org/BSD-3-Clause">`license`</a>
- ElectronNET.API <a href="https://licenses.nuget.org/MIT">`license`</a>
- FFmpeg.AutoGen <a href="https://www.nuget.org/packages/FFmpeg.AutoGen/6.0.0/license">`license`</a>
- LiteDB <a href="https://www.nuget.org/packages/LiteDB/5.0.16/license">`license`</a>
- SharpGrabber <a href="https://www.nuget.org/packages/SharpGrabber/2.1.1/license">`license`</a>
- SharpGrabber.Adult <a href="https://www.nuget.org/packages/SharpGrabber.Adult/1.0.2/license">`license`</a>
- SharpGrabber.Hls <a href="https://www.nuget.org/packages/SharpGrabber.Hls/1.3.0/license">`license`</a>
- SharpGrabber.YouTube <a href="https://www.nuget.org/packages/SharpGrabber.YouTube/1.5.0/license">`license`</a>

# External libraries (Can be downloaded automaticly within settings view)
- FFmpeg 6.0 <a href="https://ffmpeg.org/legal.html">`license`</a>

# More Details
- German: https://github.com/hswlab/dist-pronothek/blob/main/about-de.pdf
- English: https://github.com/hswlab/dist-pronothek/blob/main/about-en.pdf
