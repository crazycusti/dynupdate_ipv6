# dynupdate_ipv6
ddclient and inadyn does not support simultaneous ipv4 and ipv6 updates for dyn.com (no idea why)
only the original dyn.com updateclient (gui based!) can update them.

so, this script can handle this. its unsecure (plaintext password woohoo!) but it works for me.

short install:

- edit the script (username, password, hostname, ipv6 address)
- copy to /usr/bin
- chmod +x /usr/bin/dynclient (to made them executable)
- run crontab -e as your favorite user (dolan plz do no't root) and set the timer. (example crontab)
- have fun
