## PHP-OPENCV - PHP extension for OpenCV

[![Build Status](https://travis-ci.org/php-opencv/php-opencv.svg?branch=master)](https://travis-ci.org/php-opencv/php-opencv) [![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%207.0-8892BF.svg)](https://php.net/)

### Easy installation on ubuntu 20.10 LTS from precompiled packages:
```
apt update && apt install -y wget && \
wget https://raw.githubusercontent.com/php-opencv/php-opencv-packages/master/opencv_4.5.0_amd64.deb && dpkg -i opencv_4.5.0_amd64.deb && rm opencv_4.5.0_amd64.deb && \
wget https://raw.githubusercontent.com/php-opencv/php-opencv-packages/master/php-opencv_8.0-4.5.0_amd64.deb && dpkg -i php-opencv_8.0-4.5.0_amd64.deb && rm php-opencv_8.0-4.5.0_amd64.deb && \
echo "extension=opencv.so" > /etc/php/8.0/cli/conf.d/opencv.ini
```
[All installation options](https://github.com/php-opencv/php-opencv/wiki/Installation)

### Examples
- [dnn](https://github.com/php-opencv/php-opencv-examples)
- [core](https://github.com/hihozhou/php-opencv)

### Documentation
- [PHP OpenCV Doc](https://phpopencv.org/docs/index.html)
- [PHP OpenCV Api](https://phpopencv.org/api/index.html)

### Requirements
- OpenCV 4.0.0+
- PHP 7.0 / 7.1 / 7.2 / ~~7.3~~ / 7.4 / 8.0

### Features
- [core](https://phpopencv.org/docs/mat.html)
- [imgproc](https://phpopencv.org/docs/gausian_median_blur_bilateral_filter.html)
- highgui
- objdetect
- video
- ml
- dnn

### Helper for autocomplete and highlighting in your IDE
- [phpdoc file](https://github.com/php-opencv/php-opencv-examples/blob/master/phpdoc.php)
- [php-opencv-ide-helper](https://github.com/hihozhou/php-opencv-ide-helper)

### Contributors
- [@morozovsk](https://github.com/morozovsk)
- [@hihozhou](https://github.com/hihozhou)
- [@MaleicAcid](https://github.com/MaleicAcid)
