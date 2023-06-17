# Downloadthek Video Downloader
[![GitHub](https://img.shields.io/github/license/hswlab/downloadthek)](https://github.com/hswlab/downloadthek/blob/main/LICENSE)
[![Downloads](https://img.shields.io/github/downloads/hswlab/downloadthek/total)](https://github.com/hswlab/downloadthek/releases/latest)
[![Downloads](https://img.shields.io/github/v/release/hswlab/downloadthek)](https://github.com/hswlab/downloadthek/releases/latest)

This application is an experiment to convert a .NET6 MVC web application into a fully functional 
desktop application using Electron .NET. User interactions such as configuring storage folders or 
editing video are uncommon in a classic web application. This is where Electron's strengths come into 
play, as it allows you to perform actions closer to the operating system. Among other things, this 
application serves as an experimentation environment for me to learn how to use ffmpeg in C#. 
Currently, I am trying to understand how video streams work and how to retrieve and convert such 
data. Perhaps this experiment will develop into at least a useful video downloader for various 
streams/media. To determine a downloadable video URL, my downloader uses the SharpGrabber 
library, so only downloads on media platforms that support this library are possible. More download 
possibilities will be available once I have delved deeper into the subject.

- Currently Supported Websites: YouTube, xvideos, xnxx

![preview](https://github.com/hswlab/downloadthek/blob/main/Screenshot.png)

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
- MediaToolkit <a href="https://www.nuget.org/packages/SharpGrabber.YouTube/1.5.0/license">`license`</a>

# External libraries (Can be downloaded automaticly within settings view)
- FFmpeg 6.0 <a href="https://ffmpeg.org/legal.html">`license`</a>

# More Details
- German: https://github.com/hswlab/downloadthek/blob/main/about-de.pdf
- English: https://github.com/hswlab/downloadthek/blob/main/about-en.pdf
