# ofxARToolKitPlus

original ofxAddons from 
https://github.com/karldd/ofxARToolkitPlus

and open source library from
https://launchpad.net/artoolkitplus

-deprecated codeblock example

+xcode example from 

for your costum compilationn
build the static library rather that shared library

in CMakeLists.txt line 32
comment 
    #add_library(ARToolKitPlus SHARED ${HEADERS_AR} ${SOURCES_AR})
replace with
	add_library(ARToolKitPlus STATIC ${HEADERS_AR} ${SOURCES_AR})