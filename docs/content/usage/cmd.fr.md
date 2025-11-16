---
title: "Command Line Usage"
---

Le Simple DHCP Serveur fournit plusieurs options pour l'exécuter, en fonction de
la méthode d'installation.

* Obtenir de l'**aide**:

    ```sh
    simple-dhcp-server
    ```

* Tk **User Interface**:

    ```sh
    simple-dhcp-server-tk
    ```

* QT **User Interface**:

    ```sh
    simple-dhcp-server-qt
    ```

* **Command Line** start a server:

    ```sh
    simple-dhcp-server-serve
    ```

* **Command Line** just listening to what is going on:

    ```sh
    simple-dhcp-server-listen
    ```

## Linux (sudo)

Sous Linux, vous devez exécuter les commandes avec `sudo` pour accéder au
réseau. Car le port DHCP 67 est inférieur à 1024.
