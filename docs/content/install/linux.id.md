---
title: "Linux"
---

## Desktop Starter

You can download a single starter file to start the Simple DHCP Server. Navigate
to the [releases][You can download a single starter file to start the Simple
DHCP Server. Navigate to the [releases]{1} and download
`simple-dhcp-server.desktop`.] and download `simple-dhcp-server.desktop`.

1. Install the [pipx] package.
2. Double-click the downloaded file and mark it as executable.
3. Enter the super user password to start the Simple DHCP Server.

## Debian/Ubuntu

On Ubuntu, you have the choice to install the package via [source][On Ubuntu,
you have the choice to install the package via [source]{1}.].

If you would like to use the Tk frontend, also intall these packages:

```sh
sudo apt-get install python3 python3-tk
pip install simple-dhcp-server
```

## Other Systems

On all Linux systems, you can install the [source package][On Ubuntu, you have
the choice to install the package via [source]{1}.].

## Usage

After installation, refer to the [usage][After installation, refer to the
[usage]{1}.].

[On Ubuntu, you have the choice to install the package via [source]{1}.]:
source.md
[You can download a single starter file to start the Simple DHCP Server.
Navigate to the [releases]{1} and download `simple-dhcp-server.desktop`.]:
https://github.com/niccokunzmann/simple_dhcp_server/releases
[After installation, refer to the [usage]{1}.]: /usage/cmd.md
[pipx]: https://pipx.pypa.io/stable/installation/
