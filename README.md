revlens is a multitrack media playback and review toolset.

<img src="images/revlens_bbb_Nov4_2019.png"/>

# Features - 19.05.11

## Platform support

- Linux, Windows, OSX, iOS

## Playback

- frame accurate scrubbing
- mutlithreaded lookahead caching
- gapless playback (video and audio)
- playback modes (forward, backward, ping pong)

## Format support

- Format support via plugin architecture
- Frame sequence (tif, jpg, exr, etc) and container media (mov, avi, mp4, etc)
- Audio (separate audio files or emebedded audio in media container)
- Implemented plugins: FFMpeg, OpenEXR, common image formats (tiff, jpg, etc)

## Display

- Zoom, Pan
- Linear and nonlinear encoding (OCIO support coming soon)
- real time heads up display

## Timeline

- Multitrack media
- resizable split slider
- global in / out points
- horizontal zoombar
- track visibility toggle
- extendible track actions / gear menu
- waveform display
- thumbnail display
- frame tick display (auto scaling)
- per-clip in and out points
- custom tracks

## Annotations

- per-frame annotations
- multitrack annotations
- real time held frames
- brush system
- palm rejection (iOS)

## Sync

- real time, room-based sync for arbitrary number of participants
- multitrack sync
- annotation sync

## Scripting

- embedded Python interpreter and Python API
- Javascript API for web-based tools

## Interface

- programmable, remappable hotkeys
- tiling, nonoverlapping UI panes
- custom layouts
- custom widgets (Qt / Python or Javascript / web based)
- load and save sessions
