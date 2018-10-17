# VideoSetupNX

An app for creating HTML files (using https://gbatemp.net/threads/html-video-template-nx.520956/) and converting files to switch compatible formats. (Warning: hacky and possibly shitty code here!)

__Features__
- Generates customized HTML from a folder of switch-compatible video files
- Converts video files to Switch-compatible format with optional resizing. (requires ffmpeg pre-installed)
- Burns in subtitles so you can watch your favorite anime anywhere!
- Autocreates episode preview snapshots
- Automatically sets up directories, HTML/CSS/JS files. Just drop your videos into the vids folder!

__Issues__
- None I'm aware of!

__Requirements__
FFMPEG (https://github.com/adaptlearning/adapt_authoring/wiki/Installing-FFmpeg)
You can, alternatively, just download a build from here and put the files in the bin folder in the same place as the VideoSetupNX.exe.

__Important Information__
- Videos with spaces will not work. This seems to be a limitation of the switch's browser rather than this program or the web framework.
- Videos should be encoded with H264/AAC. Other codecs/formats may work, but I know those work 100%.
- Videos must have a resolution less than or equal to 720p. Otherwise, the switch will crash.
- Please remember to checkmark "Ask for a user at launching" in the Homebrew Web Framework. The generated NSP will crash otherwise.

__Usage__

Follow each step, then hit "Generate project". It'll open the output directory when it's complete. Copy the videos you selected in Step 2 into the "vids" folder, then build the entire output folder (the stuff in the folder, not the folder itself!) with the Homebrew Web Framework.

__Screenshots__

![GUI Screenshot](http://aida.moe/share/BJeY.png)

![End Result](http://aida.moe/share/I3rd.png)

__Credits__

SuperOkazaki/OkazakiTheOtaku for their awesome HTML work (https://github.com/SuperOkazaki/HTML-Video-Template-NX)
