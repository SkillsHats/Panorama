## Ubuntu

### Compile Dependencies:

* gcc >= 4.7 (Or VS2015)
* [Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page)
* [FLANN](http://www.cs.ubc.ca/research/flann/)
* [CImg](http://cimg.eu/)
* libjpeg
* cmake or make

### Install
* sudo apt install build-essential sed cmake libjpeg-dev libeigen3-dev


```
$ make -C src
```
or
```
$ mkdir build && cd build && cmake .. && make
```

Run: ./image-stitching <file1> <file2> ...

