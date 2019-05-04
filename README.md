**ShareMount**
-----

![GitHub issues](https://img.shields.io/github/issues/darryllane/Sharemount.svg)

[![PyPI version](https://badge.fury.io/py/ShareMount.svg)](https://badge.fury.io/py/ShareMount)

**Mount Shares on Linux and MacOS**
 
>Author: Darryl Lane  |  Twitter: @darryllane101

>https://github.com/darryllane/ShareMount


**Pip Install Instructions**

Note: To test if pip is already installed execute.

`pip -V`

(1) Mac and Kali users can simply use the following command to download and install `pip`.

`curl https://bootstrap.pypa.io/get-pip.py -o - | python`

**ShareMount Install Instructions**

(1) Once `pip` has successfully downloaded and installed, we can install 'ShareMount':

`sudo pip install ShareMount`

**Example:**

    # import library
    from ShareMount import ShareMount as initiate
    
    # initialse Class
    share = initiate.Mount(mount_remote='//remote/share/path')
    
    # mount share
    share._mount()
    
    # unmount Share**
    share._un_mount()
    

Change/Feature Requests
====
* Windows Mount

Changelog
====
* Version __0.6b.0dev__ (__04/05/2019__):
  * Linux bug fis
* Version __0.1b.0dev__ (__03/05/2019__):
  * init
