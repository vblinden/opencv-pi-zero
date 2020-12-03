### OpenCV for Raspberry Pi Zero
The reason this repository exists is because compiling OpenCV for a Raspberry Pi Zero takes 12+ hours. That is a huge pain in the ass. This doesn't matter much if you just have to do it once or twice, but if you need it 10+ times it will take too much time.

#### How to install
- Download the latest version from the [release](https://github.com/vblinden/opencv-pi-zero/releases) tab.
- Extract the archive with `tar xvfz opencv.tar.gz`
- Move the folder over to the `/tmp` folder on your system.
- Run the following commands in the `/tmp/opencv/opencv-{version}/build` folder
```shell script
sudo make install
sudo ldconfig
```

The whole process should take you arround 10 minutes instea of the 12+ hours of compiling it yourself. 

If you encounter any issues, please open a new issue on GitHub.
