- You can easily convert media files on the Raspberry Pi using a piece of software called **libav-tools**. 

- The first thing to do is to download the software. Open a terminal and type the following:

```bash
sudo apt update && sudo apt install libav-tools -y
```

- You can check that it has installed by typing the following into the terminal

```bash
avconv -version
```

- To convert one format to the other, for sound or video files, you can use the following basic command.

```bash
avconv -i input.ext output.ext
```

- So for instance, to convert a wav file (`.wav`) into an mp3 file (`.mp4`) you would type:

```bash
avconv -i my_video.wav my_video.mp3
```
