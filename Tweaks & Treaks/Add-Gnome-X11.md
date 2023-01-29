# Add-gnome-X11-Fdora37

Add Gnome X11 + both classic environments on Fedora 37 (After installing Fedora 37, updates/upgrades include this for you).

If updates/upgrades don't do it for you or for whatever other reason, follow these steps:

-Open the terminal and install it with this command.

``sudo dnf install xorg-x11-xauth``

-After installation, ``sudo vi /etc/ssh/sshd_config`` modify the sshd_config;

-Change ``X11Forwarding no`` to ``X11Forwarding yes`` 

-Press ``esc`` key then type ``:w`` to save changes.

-You can log out from your current user, and a gear option should appear at the bottom right corner with new options.
