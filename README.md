# Widevine-DL
Encrypted MPD Manifest Content Downloader + Decryptor<br>

### Requirements

- ffmpeg, ytdl-p, aria2c, widevine-l3-decryptor, [mp4decrypt](https://www.bento4.com/downloads/)

```
pip install ffmpeg youtube-dl ytdl-p aria2p
```
- You must add mp4decrypt to `PATH` in order to run this script!

### Inputs
- `WideVineDecryptor Prompt` - Copy from widevine-l3-decryptor extension *(like the format below)*
```
WidevineDecryptor: Found key: 100b6c20940f779a4589152b57d2dacb (KID=eb676abbcb345e96bbcf616630f1a3da)
```
- `MPD URL` - MPD URL of Widevine Content
- `VIDEO_ID` - Video Track ID Shown in Stream Info 
- `AUDIO_ID` - Audio Track ID Shown in Stream Info 
- `FILENAME` - Desired File Name of Final Decrypted File *(with extension!)*

### Warning
- DO NOT use this for Copyright Enfringement!
