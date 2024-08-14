
8. edit /etc/fuse.conf and uncomment user_allow_others


   mkdir LinuxISO



   vmhgfs-fuse -o allow_other -o auto_unmount .host:/Linux-ISO-2022  $HOME/LinuxISO
   
9. Enable Shared Clipboard, Drag n Drop and Shared Folders.
10. Test it and everything should work fine. 
