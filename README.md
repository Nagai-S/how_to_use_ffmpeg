# how_to_use_ffmpeg
ffmpeg convert from m3u8 to mp4
```
ffmpeg -protocol_whitelist file,http,https,tcp,tls,crypto -i [入力ファイル].m3u8 -movflags faststart -c copy [出力ファイル].mp4
```
