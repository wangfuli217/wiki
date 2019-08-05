


# Unbound : DNS server

## Unbound files
* `/etc/hosts`
* `/etc/hostname`
* `/etc/resolv.conf` : fastly write : `nameserver 127.0.0.1`
* `/etc/network/interfaces`

## Unbound test

* `route add default gw 80.81.82.22`
* `unbound-checkconf /etc/unbound/unbound.conf`


# Nginx : proxy

## Nginx debug
* `sudo /etc/init.d/apache2 stop` if impossible to bind to 443 or 80