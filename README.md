# 2wavpack

Various lossless to WAVPACK while keeping the tags.

Lossless audio source supported: ALAC, APE, FLAC, WAV, WAVPACK

--------------------------------------------------------------------------------------------------
## Install & update
`curl https://raw.githubusercontent.com/Jocker666z/2ape/master/2wavpack.sh > /home/$USER/.local/bin/2wavpack && chmod +rx /home/$USER/.local/bin/2wavpack`

## Dependencies
`ffmpeg flac monkeys-audio wavpack`

## Use
Processes all compatible files in the current directory and the three subdirectories.
```
Options:
  --16bits_only           Compress only 16bits source.
  --best_compress         Use best WAVPACK compression (-hhx6).
  --re_wavpack            Recompress WAVPACK source.
  --alac_only             Compress only ALAC source.
  --ape_only              Compress only Monkey's Audio source.
  --flac_only             Compress only FLAC source.
  --wav_only              Compress only WAV source.
  -v, --verbose           More verbose, for debug.
```

Default compression is `-hhx2`, with argument --best_compress use `-hhx6`.
