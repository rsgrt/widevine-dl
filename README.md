# Widevine-DL     

Encrypted MPD Manifest Content Downloader + Decryptor (not a Widevine Key Extractor!)<br>

## Requirements
- ffmpeg, yt-dlp, aria2, KID:KEY

```
$ pip install ffmpeg yt-dlp aria2p
```

## Installation & Run
1. git clone
2. install requirements
3. run: py widevine-dl.py
```

## Inputs
- Input format: NAME_OF_FINAL_VIDEO_FILE_NO_EXTENSION;MPD_URL;KID:KEY
- `VIDEO_ID` - Video Track ID Shown in Stream Info *(Leave blank for best)*
- `AUDIO_ID` - Audio Track ID Shown in Stream Info *(Leave blank for best)*

## Legal Notice
Educational purposes only. Downloading DRM'ed materials may violate their Terms of Service.

