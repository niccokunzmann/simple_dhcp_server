---
title: "Linux"
---

## Desktop Starter

Vous pouvez télécharger un fichier de démarrage pour démarrer le Serveur DHCP
Simple. Accédez à [releases][2] et téléchargez `simple-dhcp-server.desktop`.

1. Installez le package [pipx].
2. Double-cliquez sur le fichier téléchargé et marquez-le comme exécutable.
3. Entrez le mot de passe du super utilisateur pour démarrer le serveur DHCP
   simple.

## Debian/Ubuntu

Sur Ubuntu, vous avez le choix d'installer le paquet via [source][1].

Si vous souhaitez utiliser le Tk frontend, installez également ces packages:

```sh
sudo apt-get install python3 python3-tk
pip install simple-dhcp-server
```

## Autres systèmes

Sur tous les systèmes Linux, vous pouvez installer le [source package][1].

## Utilisation

Après installation, reportez-vous à l'[utilisation][3].

[1]: source.md
[2]: https://github.com/niccokunzmann/simple_dhcp_server/releases
[3]: /usage/cmd.md
[pipx]: https://pipx.pypa.io/stable/installation/
