---
title: "Linux"
---

## Desktop Starter

You can download a single starter file to start the Simple DHCP Server. Navigate
to the [releases][2] and download `simple-dhcp-server.desktop`.

1. Install the [pipx] package.
2. Double-click the downloaded file and mark it as executable.
3. Enter the super user password to start the Simple DHCP Server.

## Debian/Ubuntu

Sur Ubuntu, vous avez le choix d'installer le paquet via [source][1].

If you would like to use the Tk frontend, also intall these packages:

```sh
sudo apt-get install python3 python3-tk
pip install simple-dhcp-server
```

## Other Systems

On all Linux systems, you can install the [source package][1].

## Utilisation

Après installation, reportez-vous à l'[utilisation][3].

[1]: source.md
[2]: https://github.com/niccokunzmann/simple_dhcp_server/releases
[3]: /usage/cmd.md
[pipx]: https://pipx.pypa.io/stable/installation/
