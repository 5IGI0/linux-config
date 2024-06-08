# Linux config

this repository contains everything i use on my linux computer \
and useful notes to install/configure it

- [i3](/i3.md)
- [DNSCrypt](https://www.dnscrypt.org/) [note](#DNSCrypt-note)

<h5 id="DNSCrypt-note">DNSCrypt note</h5>

do not forget to add this in `/etc/NetworkManager/NetworkManager.conf`
```ini
[main]
dns=none
rc-manager=unmanaged
```