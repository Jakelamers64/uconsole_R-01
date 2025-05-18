# How to make R-01 boot to Command Line rather than Desktop Enviorment

## Helpful Links:
- https://www.baeldung.com/linux/boot-linux-command-line-mode

## Commands I tried:

### Changing Systemd Target (See link)
- cat /proc/1/comm
- sudo systemctl set-default multi-user.target
- sudo reboot

I don't think you need to do this if you read the readme it recommends the following:

### Removing ttyl service and .bash_profile
- sudo rm -rf /etc/systemd/getty@ttyl.service.d/
- sudo rm ~/.bash_profile

After I did the above I was able to boot into the terminal
