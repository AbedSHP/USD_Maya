### USD and USD FOR MAYA (WINDOWS 64bit ONLY)
Built USD from PixarAnimationStudios/USD

Require for Build :
- Maya 2018 !
- visual studio 2017 14.1 MSVC or Build Tools
- Python 2.7.5 to higher
- Cmake 3.9 
- nasm 2.07 to higher

## Download adn Install

#### Maya 2018
```bash
https://www.autodesk.com/products/maya/overview
```
#### visual studio 2017
```bash
https://visualstudio.microsoft.com/downloads/
```
#### Python 2.7.5
```bash
https://www.python.org/download/releases/2.7.5/
```
#### Cmake 3.9 
```bash
https://cmake.org/files/v3.9/
```
#### nasm 2.13
```bash
https://www.nasm.us/pub/nasm/releasebuilds/2.13/
```

## Start

Copy Git and Git clone in Main Reposotory
```bash
https://github.com/PixarAnimationStudios/USD
```
For Example to :
```bash
C:\USD
```
Open CMD as Administrator and go this Directory
```bash
C:\USD\build_scripts
```
Main command for Build
```bash
python build_usd.py C:\USD\Build
```

add to ENV
```bash
C:\USD\Build\lib\python to PYTHONPATH
C:\USD\Build\bin , C:\USD\Build\lib to PATH
```

For Test
```bash
usdview C:\USD\extras\usd\tutorials\convertingLayerFormats\Sphere.usda
```















