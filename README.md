This a sub-repo of [Neard project](https://github.com/crazy-max/neard) involving Node.js binary bundles.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Installation](#installation)
- [Configuration](#configuration)
- [Download](#download)
  - [0.10](#010)
  - [0.11](#011)
  - [0.12](#012)
  - [4](#4)
  - [5](#5)
- [Sources](#sources)
- [Contribute](#contribute)
- [Issues](#issues)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Installation

* Download and install [Neard](https://github.com/crazy-max/neard).
* If you already have installed Neard, stop it.
* Download [a Node.js bundle](#download).
* Use a file archiver that supports [7z format](http://www.7-zip.org/7z.html) like [7zip](http://www.7-zip.org/) and extract the archive in `neard\bin\nodejs\`.

Directory structure example :
```
[-] neard
 | [-] bin
 |  | [-] nodejs
 |  |  | [-] nodejs0.12.9
 |  |     | neard.conf
 |  |  | [-] nodejs5.1.1
 |  |     | neard.conf
 ```

* Start Neard.
* Switch to the Node.js version you have extracted on Neard :

![](https://raw.github.com/crazy-max/neard-bin-nodejs/master/img/switchVersion-20151214.png)

## Configuration

Npm configuration is located in `neard\bin\nodejs\nodejsx.x.x\etc`.<br />
Npm cache is global and located in `neard\tmp\npm-cache`.

## Download

![](https://raw.github.com/crazy-max/neard-bin-nodejs/master/img/star-20151214.png) : Default bundle on Neard.

### 0.10

|                     | Node.js release date | Neard release | Download |
| ------------------- |:--------------------:|:-------------:|:--------:|
| **Node.js 0.10.22** | 2013/12/02 | [r2](https://github.com/crazy-max/neard-bin-nodejs/releases/tag/r2) | [neard-nodejs-0.10.22-r2.zip](https://github.com/crazy-max/neard-bin-nodejs/releases/download/r2/neard-nodejs-0.10.22-r2.zip) |
| **Node.js 0.10.38** | 2015/03/23 | [r2](https://github.com/crazy-max/neard-bin-nodejs/releases/tag/r2) | [neard-nodejs-0.10.38-r2.zip](https://github.com/crazy-max/neard-bin-nodejs/releases/download/r2/neard-nodejs-0.10.38-r2.zip) |
| **Node.js 0.10.41** | 2015/12/03 | [r2](https://github.com/crazy-max/neard-bin-nodejs/releases/tag/r2) | [neard-nodejs-0.10.41-r2.zip](https://github.com/crazy-max/neard-bin-nodejs/releases/download/r2/neard-nodejs-0.10.41-r2.zip) |

### 0.11

|                     | Node.js release date | Neard release | Download |
| ------------------- |:--------------------:|:-------------:|:--------:|
| **Node.js 0.11.9**  | 2013/12/02 | [r2](https://github.com/crazy-max/neard-bin-nodejs/releases/tag/r2) | [neard-nodejs-0.11.9-r2.zip](https://github.com/crazy-max/neard-bin-nodejs/releases/download/r2/neard-nodejs-0.11.9-r2.zip) |
| **Node.js 0.11.16** | 2015/01/30 | [r2](https://github.com/crazy-max/neard-bin-nodejs/releases/tag/r2) | [neard-nodejs-0.11.16-r2.zip](https://github.com/crazy-max/neard-bin-nodejs/releases/download/r2/neard-nodejs-0.11.16-r2.zip) |

### 0.12

|                     | Node.js release date | Neard release | Download |
| ------------------- |:--------------------:|:-------------:|:--------:|
| **Node.js 0.12.4**  | 2015/05/23 | [r2](https://github.com/crazy-max/neard-bin-nodejs/releases/tag/r2) | [neard-nodejs-0.12.4-r2.zip](https://github.com/crazy-max/neard-bin-nodejs/releases/download/r2/neard-nodejs-0.12.4-r2.zip) |
| **Node.js 0.12.9** ![](https://raw.github.com/crazy-max/neard-bin-nodejs/master/img/star-20151214.png) | 2015/12/03 | [r2](https://github.com/crazy-max/neard-bin-nodejs/releases/tag/r2) | [neard-nodejs-0.12.9-r2.zip](https://github.com/crazy-max/neard-bin-nodejs/releases/download/r2/neard-nodejs-0.12.9-r2.zip) |
| **Node.js 0.12.13** | 2016/04/01 | [r3](https://github.com/crazy-max/neard-bin-nodejs/releases/tag/r3) | [neard-nodejs-0.12.13-r3.7z](https://github.com/crazy-max/neard-bin-nodejs/releases/download/r3/neard-nodejs-0.12.13-r3.7z) |

### 4

|                     | Node.js release date | Neard release | Download |
| ------------------- |:--------------------:|:-------------:|:--------:|
| **Node.js 4.2.3**   | 2015/12/03 | [r2](https://github.com/crazy-max/neard-bin-nodejs/releases/tag/r2) | [neard-nodejs-4.2.3-r2.zip](https://github.com/crazy-max/neard-bin-nodejs/releases/download/r2/neard-nodejs-4.2.3-r2.zip) |
| **Node.js 4.2.6**   | 2016/01/21 | [r2](https://github.com/crazy-max/neard-bin-nodejs/releases/tag/r2) | [neard-nodejs-4.2.6-r2.zip](https://github.com/crazy-max/neard-bin-nodejs/releases/download/r2/neard-nodejs-4.2.6-r2.zip) |
| **Node.js 4.4.3**   | 2016/04/12 | [r3](https://github.com/crazy-max/neard-bin-nodejs/releases/tag/r3) | [neard-nodejs-4.4.3-r3.7z](https://github.com/crazy-max/neard-bin-nodejs/releases/download/r3/neard-nodejs-4.4.3-r3.7z) |

### 5

|                     | Node.js release date | Neard release | Download |
| ------------------- |:--------------------:|:-------------:|:--------:|
| **Node.js 5.1.1**   | 2015/12/03 | [r2](https://github.com/crazy-max/neard-bin-nodejs/releases/tag/r2) | [neard-nodejs-5.1.1-r2.zip](https://github.com/crazy-max/neard-bin-nodejs/releases/download/r2/neard-nodejs-5.1.1-r2.zip) |
| **Node.js 5.5.0**   | 2016/01/21 | [r2](https://github.com/crazy-max/neard-bin-nodejs/releases/tag/r2) | [neard-nodejs-5.5.0-r2.zip](https://github.com/crazy-max/neard-bin-nodejs/releases/download/r2/neard-nodejs-5.5.0-r2.zip) |
| **Node.js 5.10.1**  | 2016/04/05 | [r3](https://github.com/crazy-max/neard-bin-nodejs/releases/tag/r3) | [neard-nodejs-5.10.1-r3.7z](https://github.com/crazy-max/neard-bin-nodejs/releases/download/r3/neard-nodejs-5.10.1-r3.7z) |

## Sources

* https://nodejs.org/

## Contribute

If you want to contribute to this bundle and create new bundles, you have to download [neard-dev](https://github.com/crazy-max/neard-dev) in the parent folder of the bundle.
Directory structure example :

```
[-] neard-dev
 | [-] build
 |  |  | build-commons.xml 
[-] neard-bin-nodejs
 |  | build.xml
```

To create a new bundle :
* Do not forget to increment the `build.release` in the `build.properties` file.
* If you want you can change the `build.path` (default `C:\neard-build`).
* Open a command prompt in your bundle folder and call the Ant target `release` : `ant release`.
* Upload your release on a file hosting system like [Sendspace](https://www.sendspace.com/).
* Create an [issue on Neard repository](https://github.com/crazy-max/neard/issues) to integrate your release.

## Issues

Issues must be reported on [Neard repository](https://github.com/crazy-max/neard/issues).<br />
Please read [Found a bug?](https://github.com/crazy-max/neard#found-a-bug) section before reporting an issue.
