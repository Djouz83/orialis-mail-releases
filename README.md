# Orialis Mail : versions publiées

Ce dépôt ne contient que les fichiers compilés d'Orialis Mail, un copilote IA pour Thunderbird. Le code source est privé.

- `latest.json` : dernière version publiée, avec les empreintes SHA-256 des fichiers et une signature Ed25519. Orialis Mail la propose, et son relais local vérifie la signature avant d'installer le Setup.
- `updates.json` : lu par Thunderbird pour mettre à jour l'extension (empreinte SHA-256 vérifiée).
- Les fichiers sont joints à chaque [release](https://github.com/Djouz83/orialis-mail-releases/releases).
