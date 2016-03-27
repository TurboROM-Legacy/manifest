Welcome to Turbo ROM
===================


Getting Started
---------------

To get started with Turbo ROM, you'll need to get familiar with
[Git and Repo](http://source.android.com/download/using-repo).

Initializing:

First, create a folder to hold the source code: 

	mkdir ~/turbo 

Next, naviate into that new directory via the terminal:

	cd ~/turbo

To initialize your local repository using the Turbo ROM trees, use this command:

	repo init -u git://github.com/TurboROM/manifest.git -b m6.0.1

Then sync up with this command:

	repo sync -fcj4 --force-sync --force-broken
	
You can make the 4 higher depending on how fast your internet connection is. 


-------------
 
Building from source

First:

	cd ~/turbo

Second:

	. build/envsetup.sh

Third:

	breakfast (device codename)

Then use one of these: 

	make -j# bacon (# is number of jobs you CPU can handle)

or:

	mka bacon (Uses as much of the CPU as is possible)

(NOTE: bacon does not build the OnePlus One, it will build any device)

 
 Our official device repository:
 [TurboROM devices](https://github.com/TurboROM-Devices)
 
 
 
 Follow us on our G+ group for latest news, releases, and build support
 [Google+](https://plus.google.com/communities/100107549156816400681)
