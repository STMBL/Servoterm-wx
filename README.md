This is the old wx based servoterm. Currently we suggest using the browser based servoterm. https://github.com/STMBL/Servoterm-app
####Building Servoterm
##### Requirements
* cmake >= 2.8
* gcc >= 4.8 or clang
* wxwidgets >= 3.0
* libserialport http://sigrok.org/wiki/Libserialport

If you don't know how to get these on Ubuntu/Debian see continuous integration config: https://github.com/rene-dev/stmbl/blob/master/.travis.yml

###### OSX
* install Xcode
* install home-brew http://brew.sh
* brew install cmake wxwidgets pkg-config
* brew tap rene-dev/sigrok
* brew install --HEAD libserialport


##### Compiling

    cd term/
    mkdir build/
    cd build/
    cmake ../
    make
