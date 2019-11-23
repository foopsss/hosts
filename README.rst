My Hosts File
=============

I store here a hosts file I made for blocking porn on Android even though it can also be used on Windows, and maybe in other OS like Ubuntu or MacOS. 

    **A little bit of info: I did this for myself mainly to deal with a slight
    porn addiction, but I realize it can also be useful for someone else
    like a parent trying to avoid its children from watching porn, so I decided to upload it here**.

How-To-Host
-----------------------
- On Android an app like `AdAway
  <https://forum.xda-developers.com/showthread.php?t=2190753>`_ (root), `PornAway
  <https://forum.xda-developers.com/android/apps-games/root-pornaway-block-porn-sites-t3460036>`_ (root) or `Blokada
  <https://github.com/blokadaorg/blokada>`_ is needed. Then, `this
  <https://raw.githubusercontent.com/foopsss/hosts/master/hosts-porn>`_ URL has to be added a hosts source, and, optionally, `this list
  <https://raw.githubusercontent.com/foopsss/hosts/master/hosts-misc>`_ which blocks some miscellaneous sites.
   - Going to "system/etc" and searching for the hosts file there to add the content of the one saved here is also possible. It just has to have rw-r-r (644) permissions.
   - **Another important note**: as of Android 10 editing the system partition is not allowed and therefore, the only way to apply the file is to use the Systemless Hosts Module from Magisk which will allow anyone to use a custom hosts file from AdAway or PornAway.
- On Windows, editing it as an administrator and pasting the content of `"hosts-porn"
  <https://github.com/foopsss/hosts/blob/master/hosts-porn>`_ there works. The file is located in *c:/Windows/System32/Drivers/etc/hosts*
   - Moving it to the desktop and then editing its content may be necessary if unable to edit it from C drive.
      
Branches
--------
I keep a few branches on this project for the sake of being organized:

- **master**: this is the one you'll probably care the most for since it's the one instructions tell you to download. It has the most publicly released up to date version.
- **third**: do not ask for its name, but it's used for me to add new sites to the file, followed by a pull request to update the file found in master.
- **backup**: as the name says, it's just a copy of the up to date main master branch if it gets ruined by mistake.
   
Other useful links
-----------------------
- `PornAway hosts sources
  <https://github.com/mhxion/pornaway/tree/master/hosts>`_.
- `Airelle's hosts file
  <http://rlwpx.free.fr/WPFF/hsex.7z>`_, that blocks 481.166 sites that may have adult content (WARNING: it's a direct download for a 7-Zip file).
