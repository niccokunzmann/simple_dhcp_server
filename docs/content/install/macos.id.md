---
title: "Mac OS"
---

![](/img/macos-install.png)

To install the app, download the release `Simple.DHCP.Server.X.Y.Z.dmg` from the
[latest release][To install the app, download the release
`Simple.DHCP.Server.X.Y.Z.dmg` from the [latest release]{1}. Open it and move
the app into the Applications. Once installed like this, you can run the app.].
Open it and move the app into the Applications. Once installed like this, you
can run the app.

## Configuration and Cache

![](/img/macos-files.png)

Your configuration files are stored in `~/Library/Caches/eu.quelltext.dhcp/`.

Read more about [configuration and usage][Read more about [configuration and
usage]{1}.].

## Python Package Installation

The alternative way is to install the Python package. You should first setup
Python 3 using [brew].

```sh
brew install python-tk
```

Then, you can install the [Python package][Then, you can install the [Python
package]{1}.].

[Then, you can install the [Python package]{1}.]: ./source.md
[Read more about [configuration and usage]{1}.]: ../usage
[To install the app, download the release `Simple.DHCP.Server.X.Y.Z.dmg` from
the [latest release]{1}. Open it and move the app into the Applications. Once
installed like this, you can run the app.]:
https://github.com/niccokunzmann/simple_dhcp_server/releases
[brew]: https://brew.sh
