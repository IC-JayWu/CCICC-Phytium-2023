# Lane detection system at night based on NEON and multi-core technology

This repository is the source code of the lane line detection system under low-light conditions in the 7th Feiteng Cup of the 2023 Integrated Circuit Innovation and Entrepreneurship Competition. Using this project, it is possible to detect lane lines in low-light conditions and improve the automatic driving technology at night or in tunnels. In this project, we use multi-core, NEON and other technologies to speed up our low-light preprocessing operations.

## Dependency

+ OpenCV 3.4.14
+ GCC 9.4.0



## Usage guide

We provide four files based on the Kylin V10,which you can find on the Release page. you can use this program after the download is complete. Basic usage of the program:

```
//If you want to use initial type
cd InitialType
cd LaneDetection_Initial
cd build
make
cd ..
cp Low_Light1.mp4 ./build
cd build 
./LaneDetection_Initial

//If you want to use NEON type
cd NeonType
cd LaneDetection_Neon
cd build
make
cd ..
cp Low_Light1.mp4 ./build
cd build 
./LaneDetection_Neon

//If you want to use multicore type
cd MulticoreType
cd LaneDetection_Multicore
cd build
make
cd ..
cp Low_Light1.mp4 ./build
cd build 
./LaneDetection_Multicore

//If you want to use multicoreNeon type
cd MulticoreNeonType
cd LaneDetection_MulticoreNeon
cd build
make
cd ..
cp Low_Light1.mp4 ./build
cd build 
./LaneDetection_MulticoreNeon
```



## License

**Author: HaoJie Wu,HaoJie Wu, SongJing Gan**

**Maintainer:IC-JayWu IC.JayWu@gmail.com**
