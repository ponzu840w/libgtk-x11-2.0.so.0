# libgtk-x11-2.0.so.0
```
wget https://download.gnome.org/sources/gtk+/2.24/gtk%2B-2.24.33.tar.xz
tar -xvf gtk+-2.24.33.tar.xz
cd gtk+-2.24.33
mkdir /tmp/libgtk-build
./configure --prefix=/tmp/libgtk-build
make
make install

ls -l /tmp/libgtk-build/lib/libgtk-x11-2.0.so.0
```
