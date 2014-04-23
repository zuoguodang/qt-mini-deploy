### Qt Minimal Deployment Kits for Windows

- v5.1.1, without ICU
- v5.2.2, without ICU

```
configure -opensource -confirm-license -platform win32-g++ -make libs
		  -qt-libjpeg -q t-libpng -no-openssl -no-icu -qt-zlib -qt-pcre -no-iconv
		  -nomake examples -nomake tests -no-angle -opengl desktop -no-rtti -no-dbus
		  -strip -plugin-sql-sqlite
```