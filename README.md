OmmiROM for the Sony Xperia S (nozomi)
===========

Getting Started
---------------

To get started with OMNI ROM, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the OMNIROM trees, use a command like this:

    repo init -u git://github.com/omnirom/android.git -b android-4.4

Get our local manifest:

    curl --create-dirs -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.githubusercontent.com/omnozomi/manifest/master/sonyservice.xml

Then to sync up:

    repo sync

Then to build:

     cd <source-dir>; . build/envsetup.sh; brunch nozomi


If you need more information or a more detailed guide, click [here to see the OmniROM wiki.](http://docs.omnirom.org)
