# Widevine-DL     

Encrypted MPD Manifest Content Downloader + Decryptor (not a Widevine Key Extractor!)<br>

## Requirements
- ffmpeg, yt-dlp, aria2, KID:KEY

```
$ pip install ffmpeg yt-dlp aria2p
```

## Installation & Run
1. Download and Extract ZIP from [Releases](https://github.com/WHTJEON/widevine-dl/releases)
2. Install Requirements
3. Run widevine-dl.py
```
$ python3 widevine-dl.py
```

## Inputs
- Input format: NAME_OF_FINAL_VIDEO_FILE_NO_EXTENSION;MPD_URL;KID:KEY
- `VIDEO_ID` - Video Track ID Shown in Stream Info *(Leave blank for best)*
- `AUDIO_ID` - Audio Track ID Shown in Stream Info *(Leave blank for best)*

## Legal Notice
Educational purposes only. Downloading DRM'ed materials may violate their Terms of Service.

