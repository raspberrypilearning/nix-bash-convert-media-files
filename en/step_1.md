You can easily convert media files on the Raspberry Pi using a piece of software called **ffmpeg**. This is preinstalled on the latest versions of [Raspbian](https://www.raspberrypi.org/downloads/raspbian/). 

- To convert sound or video files from one format to another, you can use this basic command:

	```bash
	ffmpeg -i input.ext1 output.ext2
	```

- For instance, to convert a wav file (`.wav`) into an mp3 file (`.mp3`), you would type:

	```bash
	ffmpeg -i my_music.wav my_music.mp3
	```
