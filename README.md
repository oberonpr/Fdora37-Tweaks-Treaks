# Fdora37-activate-gnomex11

Fedora 37, by default, doesn't include X11 gnome; some apps still have issues with Wayland, it's hard to find the correct steps, so I'll leave them here.

First, open the terminal and install it with this command.

``sudo dnf install xorg-x11-xauth``

After installation, you need to modify the sshd_config, change ``X11Forwarding no`` to ``X11Forwarding yes``

``sudo vi /etc/ssh/sshd_config``
after changing it, hit ``esc`` key then type ``:w``

You can log out from your current desktop environment, and a gear option should appear at the bottom right corner with new options.
