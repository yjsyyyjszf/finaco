# finaco
Windows [![Build Status](http://home.draconpern.com:8080/buildStatus/icon?job=finaco.win32.release)](http://home.draconpern.com:8080/job/finaco.win32.release/) OS X [![Build Status](http://home.draconpern.com:8080/buildStatus/icon?job=finaco.osx.release)](http://home.draconpern.com:8080/job/finaco.osx.release/) Linux [![Build Status](http://home.draconpern.com:8080/buildStatus/icon?job=finaco.linux.debug)](http://home.draconpern.com:8080/job/finaco.linux.debug/)

Cross-platform software for performing PACS migration using C-MOVE.

- Supports Windows Vista and above including Windows 10
- Supported on OS X
- Works on Linux
- Fast multithreaded operations
- Stop migration midway and pick up where you left off
- Perform migration over time by getting new studies
- No dll's need to be distributed.
- Native, no Java required.

## Download
Binary http://www.draconpern.com/software/finaco
Source https://github.com/DraconPern/finaco

## Development notes
The program is http://utf8everywhere.org/
The data in sqlite is always utf8.
wxWidgets is utf32 on Windows and utf8 everywhere else.

## Requirements
- CMake http://www.cmake.org/download/
- XCode on OS X
- Visual Studio 2012 or higher on Windows
- gcc on Linux

## Third party dependency
- wxWidgets http://www.wxwidgets.org/ please extract under ./wxWidgets
- DCMTK http://dicom.offis.de/ please use snapshot or git, and extract under ./dcmtk
- boost http://www.boost.org/ please extract under ./boost
- Visual Leak Detector https://vld.codeplex.com/ installed for debug release for Windows
- zlib please extract under ./zlib on Windows
- openjpeg http://www.openjpeg.org please extract under ./openjpeg
- fmjpeg2koj https://github.com/DraconPern/fmjpeg2koj please extract under ./fmjpeg2koj

## Author
Ing-Long Eric Kuo <draconpern@hotmail.com>

## License
This software is licensed under the GPL.
