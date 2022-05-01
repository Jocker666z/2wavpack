# 2wavpack

Various lossless to WAVPACK while keeping the tags.

Lossless audio source supported: ALAC, APE, FLAC, WAV

--------------------------------------------------------------------------------------------------
## Install & update
`curl https://raw.githubusercontent.com/Jocker666z/2ape/master/2wavpack.sh > /home/$USER/.local/bin/2wavpack && chmod +rx /home/$USER/.local/bin/2wavpack`

## Dependencies
`ffmpeg flac monkeys-audio wavpack`

## Use
Processes all compatible files in the current directory and the three subdirectories.
```
Options:
  --alac_only             Compress only ALAC source.
  --ape_only              Compress only Monkey's Audio source.
  --flac_only             Compress only FLAC source.
  --wav_only              Compress only WAV source.
  --16bits_only           Compress only 16bits source.
  -v, --verbose           More verbose, for debug.
```
