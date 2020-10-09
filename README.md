# runitctl
runitctl is a simple systemctl alternative for runit
------------------
# Enable
`sudo ./runitctl enable [service]`
# Disable
`sudo ./runitctl disable [service`

# Help
```
Usage: runitctl [enable,disable] {service}
    * enable: Enables a service
    * disable: Disables a service

runitctl is a simple systemctl alternative for runit, just edit the file and change some variables depending on your distro
```

To install run `make install` after you have made your system specific changes.
