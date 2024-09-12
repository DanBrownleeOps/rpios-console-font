# rpios-console-font
Sets the /dev/tty1 console font from systemd service
For a non-GUI desktop on the RPi, the console fonts don't seem to get applied from /etc/default/console-setup. I wrote this simple service so that it would get applied before the logon prompt.
