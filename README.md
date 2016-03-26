Welcome to Turbo ROM
===================


Getting Started
---------------

To get started with Turbo ROM, you'll need to get familiar with
[Git and Repo](http://source.android.com/download/using-repo).


To initialize your local repository using the Turbo ROM trees, use this command:


	repo init -u git://github.com/TurboROM/manifest.git -b m6.0.1
	


Then sync up with this command:

	repo sync -j4 --force-sync --force-broken
	
You can make the 4 higher depending on how fast your internet connection is. 
