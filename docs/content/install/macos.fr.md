---
title: "Mac OS"
---

![](/img/macos-install.png)

Pour installer l'application, téléchargez la version
`Simple.DHCP.Server.X.Y.Z.dmg` de la [latest release][3]. Ouvrez-la et déplacez
l'application dans les Applications. Une fois installée, vous pouvez l'exécuter.

## Configuration et cache

![](/img/macos-files.png)

Vos fichiers de configuration sont stockés dans
`~/Library/Caches/eu.quelltext.dhcp/`.

En savoir plus sur [configuration and usage][2].

## Installation du package Python

L'autre solution consiste à installer le package Python. Vous devez d'abord
configurer Python 3 avec [brew].

```sh
brew install python-tk
```

Ensuite, vous pouvez installer le [Python package][1].

[1]: ./source.md
[2]: ../usage
[3]: https://github.com/niccokunzmann/simple_dhcp_server/releases
[brew]: https://brew.sh
