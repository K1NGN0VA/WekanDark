# WekanDark
Dark Theme CSS for Wekan

# No Warranty
This CSS isnt pretty. 

Mounting the head.html file doesn't remove the original head.html, so if you need to uninstall it will revert back to normal.

# Install with SNAP version of Wekan

**Install**


    $ sudo cp /snap/wekan/current/programs/web.browser/head.html head.html
    $ sudo echo '<link type="text/css" rel="stylesheet" href="https://k1ngn0va.github.io/WekanDark/WekanDark.css" />' >> head.html
    $ sudo mount --bind -o nodev,ro head.html /snap/wekan/current/programs/web.browser/head.html 
    $ systemctl restart snap.wekan.wekan



**Uninstall**


    $ sudo umount /snap/wekan/current/programs/web.browser/head.html 
    $ systemctl restart snap.wekan.wekan
    
