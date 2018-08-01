


### 1. protobuf

`sudo apt-get install protobuf-compiler libprotobuf-dev`

### 2. glog


### 3. dlib


### 4. gflags
`sudo apt-get install libgflags-dev`

### 5. ffmpeg
sudo apt-get install ffmpeg
sudo apt-get install libav-tools
sudo apt-get install libde265-0 libde265-dev libde265-examples
sudo apt-get install libavcodec-dev libavdevice-dev libavfilter-dev libavformat-dev libavutil-dev libpostproc-dev libswresample-dev libswscale-dev

### 6. qt5
sudo apt-get install qt5-default qt-creator



## Make raintime

### Download raintime and plumber-ir

Put plumber-ir in `raintime/third_party/`
and change it's name to `plumber_ir`.

### build raintime

`mkdir build && cd build`
`cmake .. -DCMAKE_BUILD_TYPE=Release -DBUILD_ON_RAINMAN_BOARD=ON -DDEF_FIXED_NUM_FB_16=9`
`make -j2`


## Make librainman

### Download librainman

### build librainman

`mkdir build && cd build`
`cmake ..`
`make -j2`


##  
