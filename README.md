This repository is for some scripts for dealing with audio files.

## Recoding audio files

The script [`recodeaudio`](src/recodeaudio) let you recode audio files into high quality
MP3, OGG or Opus formats preserving (or setting) tags.


### Prerequisites

For OGG Vorbis files: `oggenc`, `oggdec` and `ogginfo` for encoding,
decoding and querying metadata respectively.

For Opus files: `opusenc`, `opusdec` and `opusinfo` for encoding,
decoding and querying metadata respectively.

For MP3 files: `lame` for encoding and decoding, `mp3info` or `id3info` for
querying metadata.

For FLAC files: `flac` for encoding and decoding, `metaflac` for querying
metadata.
