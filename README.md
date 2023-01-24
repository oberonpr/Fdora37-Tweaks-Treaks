# Fdora37-add-gnome-X11

Add Gnome X11 + both classic environments on Fedora 37 (After installing Fedora 37, updates include this for you).

In case updates don't do it for you, follow these steps.

First, open the terminal and install it with this command.

``sudo dnf install xorg-x11-xauth``

After installation, you need to modify the sshd_config, change ``X11Forwarding no`` to ``X11Forwarding yes``

``sudo vi /etc/ssh/sshd_config``
after changing it, hit ``esc`` key then type ``:w``

You can log out from your current desktop environment, and a gear option should appear at the bottom right corner with new options.
