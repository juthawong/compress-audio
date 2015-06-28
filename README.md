# compress-audio
Convert audio folders easily to aac/m4a with ffmpeg/libfdk_aac, or to obsolete mp3.

You can also use it to extract the audio track from videos.

## Installation

Copy the script "Compress Audio" to ~/bin or /usr/local/bin

Associate folders with "Compress Audio" by selecting "Open With... -> Other Application..." in the file manager.

If you cannot associate this script with folders when selecting "Open with..." in the file manager, you should consider switching to "Nemo" (a fork of Nautilus).

On the other hand you can use it from the command line.

## License
AGPL v3.0 or later

## Notes

I used it with the file manager "Nemo" (a fork from Nautilus) so if you cannot associate this script with folders when selecting "Open with..." in the file manager, you should consider switching to Nemo


Its first purpose was to convert heavy mp3 files to aac/m4a on mp3 players. You have the option to delete the original files.

Covers are copied from the original file or added from the first *cover* *artwork* or *folder* png/jpg found in the sound file folder

Dependencies: 
- ffmpeg 
- zenity
- eyeD3
- convert
- AtomicParsley



