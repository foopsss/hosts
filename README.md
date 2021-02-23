# My Hosts File

I store here two hosts files, being one I made for blocking porn sites the one I spend the most time working on. They can be used on Windows, Android, Linux and macOS.

    A little bit of info: I did this for myself mainly, to deal with a slight
    porn addiction but I realize it can also be useful for someone else
    like a parent trying to avoid its children from watching porn, so I decided to upload it here.
    
# Installation

## Desktop Operative Systems
For these OSs is recommended to open the already existing file and just add the contents of the desired hosts file there.
* **Windows**: the file is located in *C:\Windows\System32\drivers\etc\hosts* and it can be directly opened with Notepad or Wordpad to 
be modified. It can also be opened with the "Execute" function using this command: "*notepad c:\windows\system32\drivers\etc\hosts*"
(or "*wordpad c:\windows\system32\drivers\etc\hosts*" alternatively).
* **Linux**: the file is located in the */etc/* folder and it can be opened with any text editor through a Terminal session
using the command "*sudo -name of the editor- /etc/hosts*". 
Please note that it requires root privileges do to it being in the root of the drive.
  * For example, if I were to use the built-in Nano text editor I would put *sudo nano /etc/hosts*.
* **macOS**: the file is also located in */etc/*, just like Linux and it can be opened with any text editor chosen by the user through a 
Terminal session using "*sudo -name of the text editor chosen- /etc/hosts*".
  * For example, if the user chooses to use the VIM GUI Editor the command would be *sudo vim /etc/hosts*.
  
## Mobile Operative Systems
* **Android**: similarly to the last two OSs, the file is located in *system/etc* and can be modified in a series of ways:
  * Using an app like [AdAway](https://forum.xda-developers.com/showthread.php?t=2190753) (root), [PornAway](https://forum.xda-developers.com/android/apps-games/root-pornaway-block-porn-sites-t3460036) (root) or [Blokada](https://github.com/blokadaorg/blokada) with the raw addresses of the files (take for example [hosts-porn](https://raw.githubusercontent.com/foopsss/hosts/master/hosts-porn)) as hosts sources. 
  * Editing the file located in *system* and directly pasting everything there. It can also be taken outside the device and edited in a computer, just take in mind that when it's put back into system it has to have rw-r-r (644) permissions.
  
**An important note**: On Android 10 and later releases the system partition cannot be modified so a Magisk module is required to make AdAway and PornAway work systemlessly, which can be obtained from Magisk settings under the "Systemless Hosts" option. Some custom ROMs may allow the use of "adb remount" if they they have debugging builds.

# Other useful links
* [PornAway's hosts sources](https://github.com/mhxion/pornaway/tree/master/hosts).
* [Airelle's hosts file](http://rlwpx.free.fr/WPFF/hsex.7z), that blocks 481.166 sites which may have adult content (WARNING: it's a direct download for a 7-Zip file).

# Some due credits
* PerfectSlayer for his AdAway app, that thaught me how a hosts file works.
* Christopher Welker, because I've copied some of the instructions listed on his "[How to Edit Your Hosts File on Windows, Mac, or Linux](https://www.howtogeek.com/howto/27350/beginner-geek-how-to-edit-your-hosts-file/)" article.
