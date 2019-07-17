My Hosts File
=============

I store here a hosts file I made for blocking porn on Android even though it can also be used on Windows, and maybe in other OS like Ubuntu or MacOS. 

    **A little bit of info: I did this for myself mainly to deal with a slight
    porn addiction, but I realize it can also be useful for someone else
    like a parent trying to avoid its children from watching porn, so I decided to upload it here**.

How-To-Host
-----------------------
- On Android an app like `AdAway
  <https://forum.xda-developers.com/showthread.php?t=2190753>`_, `PornAway
  <https://forum.xda-developers.com/android/apps-games/root-pornaway-block-porn-sites-t3460036>`_ or `Blokada
  <https://github.com/blokadaorg/blokada>`_ is needed. Then, you have to add `this
  <https://raw.githubusercontent.com/foopsss/hosts/master/hosts-porn>`_ URL as a hosts file source. You can also try `this list
  <https://raw.githubusercontent.com/foopsss/hosts/master/hosts-misc>`_ which blocks some miscellaneous sites I want it to.
   - You may also go to "system/etc" and search for the hosts file there to add the content of the one saved here. Do not forget to give it rw-r-r (644) permissions.
- On Windows, you have to edit it (located in *c:/Windows/System32/Drivers/etc/hosts*) with Notepad or any other text editor as an administrator and paste the content of `"hosts-porn"
  <https://github.com/foopsss/hosts/blob/master/hosts-porn>`_ there.
   - Moving the file to the desktop and then editing it may be necessary, if unable to edit it from C:.
   
Other useful links
-----------------------
- `PornAway hosts sources
  <https://github.com/mhxion/pornaway/tree/master/hosts>`_.
- `Airelle's hosts file
  <http://rlwpx.free.fr/WPFF/hsex.7z>`_, that blocks 481.166 sites that may have adult content (WARNING: it's a direct download for a 7-Zip file).
