# archautoinstaller
Arch menu selection auto installer of favorite programs
The following prerequisite are required to use this fully within Arch.
  #1 - Install Snapd
  #2 - Install AUR (currently Trizen)
  
  How to install Trizen AUR *Working on this being in the script for you*
  $ git clone https://aur.archlinux.org/trizen.git
  $ cd trizen
  $ sudo makepkg -si
  
  How to install Snaps
  - First install Trizen or other AUR
  - $ Trizen -S snapd 
  
  See Arch Wiki: https://wiki.archlinux.org/index.php/Snap
  
  Instructions
    *Install Snapd (for packages that use Snaps) See Above
    *Install Trizen (AUR for packages that require AUR) See above
    - Download bash script to a folder (ex: /Documents or /Downloads)
    - Right click on file to give execute permissions
    - Go to terminal and change to directory where you put downloaded file (ex: cd Downloads)
    - Type in terminal sudo ./installscript to run
        - You may also need to type chmod +x ./installscript if you forgot to do step 2
    - A menu will open up with selectable packages to install
    - Select packages and click OK
    - Packages will auto-install
  
  
