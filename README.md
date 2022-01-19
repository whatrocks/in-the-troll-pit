# In The Troll Pit

Podcast website and feed

## Useful commands

Download mp3 file of YouTube video

```bash
youtube-dl --extract-audio --audio-format mp3 -o "%(title)s.%(ext)s" https://youtu.be/vIlgxUoL9a4
```

Get file size of mp3 in bytes 

```bash
wc -c < 1-apple-iie-floppy-drive-setup.mp3
```


Get duration in seconds of mp3

```bash
ffprobe -show_entries stream=duration -of compact=p=0:nk=1 -v fatal 1-apple-iie-floppy-drive-setup.mp3
```