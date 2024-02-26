# gstreamer-rgaconvert
video size colorspace convert for rockchip rga hardware


### build && install

sudo apt install meson gcc cmake libgstreamer-plugins-base1.0-dev

mkdir build

cd build

meson --prefix=/usr

#sudo ninja install

cp plugins/libgstrgaconvert.so /usr/lib/aarch64-linux-gnu/gstreamer-1.0/

sudo ldconfig
