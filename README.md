# Installation:
- download binary from https://github.com/yt-dlp/yt-dlp
- download ffmpeg from https://ffmpeg.org/ for mp3 audio
- System Preferences>Security & Privacy>General>Unlock the lock, open unverified app anyway
- how to run executable in terminal:
    - `chmod -x ./filename`
    - `./filename`

# Download a video:
- `./yt-dlp_macos 'www.youtube.com/watch?v=qAeybdD5UoQ'`

# Download just audio:
- `./yt-dlp_macos -f 'ba' -x --audio-format mp3 'www.youtube.com/watch?v=qAeybdD5UoQ' --ffmpeg-location './ffmpeg'`

# Download audio playlist:
- `./yt-dlp_macos -f 'ba' -x --audio-format mp3 --yes-playlist 'https://www.youtube.com/watch?v=lHk3IERGkbI&list=PL3KCEdRCWfP23319Og8f7zZJ-JUMZfarg' --ffmpeg-location './ffmpeg'`

# Troubleshooting:
- urlopen error EOF occurred in violation of protocol (_ssl.c:1125)
 - get a better, more consistent internet connection

# To download:
./yt-dlp_macos -f 'ba' -x --audio-format mp3 'https://www.youtube.com/watch?v=bAGaY3f9HOI' --ffmpeg-location './ffmpeg'
