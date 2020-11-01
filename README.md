# WekanDark
Dark Theme CSS for Wekan

[![https://github.com/K1NGN0VA/WekanDark/blob/master/2019-04-27%2020_35_54-Test%20-%20MCG%20CWKanban%20-%20Brave.png?raw=true](https://github.com/K1NGN0VA/WekanDark/blob/master/2019-04-27%2020_35_54-Test%20-%20MCG%20CWKanban%20-%20Brave.png?raw=true "https://github.com/K1NGN0VA/WekanDark/blob/master/2019-04-27%2020_35_54-Test%20-%20MCG%20CWKanban%20-%20Brave.png?raw=true")](https://github.com/K1NGN0VA/WekanDark/blob/master/2019-04-27%2020_35_54-Test%20-%20MCG%20CWKanban%20-%20Brave.png?raw=true "https://github.com/K1NGN0VA/WekanDark/blob/master/2019-04-27%2020_35_54-Test%20-%20MCG%20CWKanban%20-%20Brave.png?raw=true")

# No Warranty
This CSS isnt pretty. 

# Install with SNAP version of Wekan

**Install**


    $ sudo cp /snap/wekan/current/programs/web.browser/head.html head.html
    $ sudo echo '<link type="text/css" rel="stylesheet" href="https://kenzokai.github.io/WekanDark/WekanDark.css" />' >> head.html
    $ sudo mount --bind -o nodev,ro head.html /snap/wekan/current/programs/web.browser/head.html 
    $ systemctl restart snap.wekan.wekan



**Uninstall**


    $ sudo umount /snap/wekan/current/programs/web.browser/head.html 
    $ systemctl restart snap.wekan.wekan
    
