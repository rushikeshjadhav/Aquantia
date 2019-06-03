# Aquantia
Aquantia AQtion NIC Driver

## To build the driver yourself, go on your docker host and use follwing shell commands to build it.

mkdir driver-aquantia

cd driver-aquantia

git clone https://github.com/xcp-ng/xcp-ng-build-env

git clone https://github.com/rushikeshjadhav/Aquantia

chown 1000 ./Aquantia/ -R

### For Release 7.6
./xcp-ng-build-env/run.py -b 7.6 --build-local Aquantia/ --rm

### For Release 8.0
./xcp-ng-build-env/run.py -b 8.0 --build-local Aquantia/ --rm
