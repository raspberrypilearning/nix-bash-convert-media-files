You can easily convert media files on the Raspberry Pi using a piece of software called **libav-tools**. 

- The first thing to do is to download the software. Open a terminal and type the following:

	```bash
	sudo apt update && sudo apt install libav-tools -y
	```

- Check that the software has installed by typing the following into the terminal:

	```bash
	avconv -version
	```

- To convert sound or video files from one format to another, you can use this basic command:

	```bash
	avconv -i input.ext1 output.ext2
	```

- For instance, to convert a wav file (`.wav`) into an mp3 file (`.mp3`), you would type:

	```bash
	avconv -i my_video.wav my_video.mp3
	```
