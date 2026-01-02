![Java](https://img.shields.io/badge/Java-1.3-b07219)
[![QuickMVC](https://img.shields.io/badge/Quick%20MVC-Applied-magenta)](https://github.com/umjammer/umjammer/blob/wiki/QuickMVC.md)

# vavi-apps-appleii-bdj

Apple II emulator for BD-J

![image](https://lh3.googleusercontent.com/tZH1VQzFHGEoj11E7QMQWWpLlW0lJfAmzSDSNf4bQK8O877OnRdVHtQBqFBKjbasbB6d3Wto6Zjr6_2dNg=w782-h440-rw)

### Published

http://www.ps4news.com/forums/playstation-3-psn-news/playstation-3-bd-j-apple-ii-emulator-released-100986.html

## Install

- [maven](https://github.com/umjammer/vavi-apps-appleii-bdj)

### build & run

```shell
$ ant sign
$ ant run
```

## Usage

### configuration

 - locate at `src/main/resources` folder
   - APPLE2E.ROM
   - disks (.dsk, .nib)

### manual

 - [appleii.txt](appleii.txt)

## References

 * https://github.com/umjammer/xletview

### Tech Know

 * until `ant sign` use jdk 1.8
 * `ant run` use jdk 17 later

## TODO

 * ~~asm treat array `XFile[]`~~
