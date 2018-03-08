# Dependencies
## Only Lidar
```
sudo apt install cmake libproj-dev libcv-dev libpcap-dev libboost-all-dev libyaml-cpp-dev libjpeg-dev libgdal-dev libpq-dev libvtk6-dev libvtk6-qt-dev libpcl-dev 
```

## Camera + Lidar

### 1. install dependencies
```
sudo apt install cmake libproj-dev libpcap-dev libboost-all-dev libyaml-cpp-dev libjpeg-dev libgdal-dev libpq-dev libvtk6-dev libvtk6-qt-dev libpcl-dev 
```
### 2. build
```
mkdir build
cd build 
 (Lidar )cmake ..  / cmake -DCamera_Enable=ON .. (Lidar + Camera)
make -j4
```
