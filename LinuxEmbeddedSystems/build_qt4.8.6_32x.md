#### Build Qt 4.8.6 For 32 bit
___
```bash
tar xzf qt-everywhere-opensource-src-4.8.6.tar.gz

cd qt-everywhere-opensource-src-4.8.6

./configure -v \
       -release \
       -prefix /opt/qt4.8.6 \
       -opensource \
       -developer-build \
       -no-webkit \
       -nomake examples \
       -nomake demos \
       -nomake docs \
       -fast \
       -qt-gfx-vnc




make -j4

sudo make install
```
