Welcome to Turbo ROM
===================


Getting Started
---------------

To get started with Turbo ROM, you'll need to get familiar with
[git and repo](http://source.android.com/source/downloading.html).

Initializing:

First, create a folder to hold the source code: 

	mkdir ~/turbo 

Next, naviate into that new directory via the terminal:

	cd ~/turbo

To initialize your local repository using the Turbo ROM trees, use this command:

	repo init -u git://github.com/TurboROM-Legacy/manifest.git -b m

Then sync up with this command:

	repo sync -fcj4 --force-sync --force-broken
	
You can make the 4 a higher or lower number depending on how fast your internet connection is. 


-------------
 
Building from Source

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

 NOTE: 'bacon' does not build the OnePlus One. You use this command for whatever device you have.

 
Our official device repositories:
[Turbo ROM devices](https://github.com/TurboROM-Devices)
 
 
 
Follow us on our G+ group for latest news, releases, and build support.
[Google+](https://plus.google.com/communities/100107549156816400681)
