# youtube-mp3
A simple command line app to download a youtube video, convert it to an mp3, and write mp3 metadata to the output file.

## Installation

*Prerequisites:* You must have nodejs installed on your machine, you can get it [here](https://nodejs.org/en/).

```bash
git clone https://github.com/efossier/youtube-mp3
cd youtube-mp3
npm install -g
youtube-mp3 -h
```

## Usage

```bash
youtube-mp3 [options] <youtube_url>

A simple command line tool to download a youtube video and convert it to an mp3 (v1.2.0)

Options:

-h, --help                   output usage information
-V, --version                output the version number
-o, --output <output_file>   output the final mp3 to this file name
-i, --intermediate           output intermediate downloaded video file
-l, --low-quality            download the video at low quality settings
-v, --verbose                print additional information during run, useful for debugging
-s, --separator <separator>  set the seperator for artist/song in video title
-b, --bitrate <rate>         set the output mp3 bitrate in kbps
```
