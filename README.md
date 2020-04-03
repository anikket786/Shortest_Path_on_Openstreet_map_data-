# Shortest path Planning Project 

This software helps to find the shortest path between two given nodes on OpenStreet map data using A-star search algorithm. Open street map is a map of the world create b the open-source community. All the data is stored in XML file format. For more infor refer [here](https://www.openstreetmap.org/#map=4/21.88/82.88)

## Cloning

While cloning this project, be sure to use the `--recurse-submodules` flag. Using HTTPS:
```
git clone https://github.com/anikket786/Shortest_Path_on_Openstreet_map_data-.git. --recurse-submodules
```

## Compiling and Running

### Compiling
To compile this project you will need a modern C++ compiler with c++14 support enabled. Then first create a `build` directory and change to that directory:
```
mkdir build && cd build
```
From within the `build` directory, run `cmake` and `make` as follows:
```
cmake ..
make
```
### Running
The executables will be placed in the `bin` directory. From within `build`, you can run the project as follows:
```
../bin/<name-of-parent-directory> -f ../map.osm
```
