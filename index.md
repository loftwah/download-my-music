# Bootleg my music... For science! and whatever

## /me assumes you're using Ubuntu, if not you know what to do. ಠ_ಠ

- ಠ_ಠ I'm watching you!!! Ubuntu! Do it... /me shakes fist

```bash
# First, update the package list
apt update

# Check if ffmpeg is already installed
if ! type "ffmpeg" > /dev/null; then
  # If it is not installed, install it
  apt install ffmpeg -y
fi

# Install neofetch
apt install neofetch -y

# Run neofetch to show that you are using Ubuntu
neofetch

# Download the latest version of youtube-dl
curl -L https://yt-dl.org/downloads/latest/youtube-dl -o youtube-dl

# Make youtube-dl executable
chmod a+rx youtube-dl

# Use youtube-dl to download the audio from a YouTube playlist in mp3 format
youtube-dl -x --audio-format mp3 -o "%(title)s.%(ext)s" https://www.youtube.com/playlist?list=PLKBAUoCO_FtkHiwRzyGzfhauIhNMBFw66
```
```

> **Protip** You can use youtube-dl to download audio from other sources as well. Just replace the URL with the URL of the source you want to download from.

> **Protip number two** You can use curl and cht.sh to quickly look up commands and other information instead of memorizing them.

- [BTSMF.LINK](https://btsmf.link)
- [loftwah (Dean Lofts)](https://github.com/loftwah)