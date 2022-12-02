# Opencv  
## Opencv安装  
[Ubuntu20.04 安装Opencv](https://blog.csdn.net/qq_40114620/article/details/107902410?spm=1001.2101.3001.6650.18&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EESLANDING%7Edefault-18-107902410-blog-122994933.pc_relevant_landingrelevant&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EESLANDING%7Edefault-18-107902410-blog-122994933.pc_relevant_landingrelevant&utm_relevant_index=25)  
## Opencv常见BUG  
### 1.Make过程中Libtiff出错  
```shell
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFReadRGBAStrip@LIBTIFF_4.0'
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFReadDirectory@LIBTIFF_4.0'
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFWriteEncodedStrip@LIBTIFF_4.0'
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFIsTiled@LIBTIFF_4.0'
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFWriteScanline@LIBTIFF_4.0'
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFGetField@LIBTIFF_4.0'
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFScanlineSize@LIBTIFF_4.0'
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFWriteDirectory@LIBTIFF_4.0'
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFReadEncodedTile@LIBTIFF_4.0'
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFReadRGBATile@LIBTIFF_4.0'
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFClose@LIBTIFF_4.0'
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFClientOpen@LIBTIFF_4.0'
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFRGBAImageOK@LIBTIFF_4.0'
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFOpen@LIBTIFF_4.0'
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFReadEncodedStrip@LIBTIFF_4.0'
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFSetField@LIBTIFF_4.0'
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFSetWarningHandler@LIBTIFF_4.0'
/usr/local/lib/libopencv_imgcodecs.so.4.2.0: undefined reference to `TIFFSetErrorHandler@LIBTIFF_4.0'
```
  
[解决方案](https://blog.csdn.net/jiaken2660/article/details/117036606?spm=1001.2101.3001.6650.4&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-4-117036606-blog-84256438.pc_relevant_recovery_v2&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-4-117036606-blog-84256438.pc_relevant_recovery_v2&utm_relevant_index=5)  
## 2.
