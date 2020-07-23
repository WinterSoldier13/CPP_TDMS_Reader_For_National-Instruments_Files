Modified by WinterSoldier13, added output to a txt file of various channels.
Based on libtdms by Ion Vasilief.




libtdms GNU GPL v. 3.0
——————————————————————
AUTHOR: Ion Vasilief
——————————————————————
FEATURES: libtdms is a C++ library for reading National Instruments TDMS files (http://www.ni.com/white-paper/3727/en).
————————————————————————————————————————————————————————————————————————————————————————————————————
LICENSE: GNU GPL v. 3.0 for open source applications. 
	For commercial applications you need a commercial license from IONDEV SRL (http://iondev.ro).
————————————————————————————————————————————————————————————————————————————————————————————————————
CREDITS: libtdms is based on the "tdmsreader" project: https://github.com/shumway/tdmsreader
————————————————————————————————————————————————————————————————————————————————————————————————————
COMPILING: 
	On Unix-like systems (Linux, macOS, etc...) a Makefile for building a static version of the library is provided in the source archive. 
	All you need to type is: 
	$ make
	
	On Windows you may use the file Makefile.win. It was tested with the MinGW compiler. You need to type: 
	$ make -f Makefile.win
	
	For users that feel more comfortable using the qmake build system from Qt (https://www.qt.io/) we provide the libtdms.pro file. You need to type:
	$ qmake
	$ make

————————————————————————————————————————————————————————————————————————————————————————————————————
