# Swissfer für Debian 13

Inoffizielles Paket von [Blutsh/swissfer](https://github.com/Blutsh/swissfer), Version 3.0.1, für **amd64 (Intel/AMD 64-Bit)**.

## Download und Installation

[Debian-Paket öffnen](packages/swissfer_3.0.1-1~deb13u1_amd64.deb) und dort **Download raw file** wählen. Dieses Repository ist privat; melde dich dafür bei GitHub an.

```sh
sudo apt install ./swissfer_3.0.1-1~deb13u1_amd64.deb
swissfer --help
```

## Quellen und Prüfung

Unter `packages/` liegen das Debian-Paket, das Quellarchiv mit Build-Skript, die Anleitung, SHA256-Prüfsummen und das Build-/Testprotokoll.

Upstream-Commit: `87fd6771421dda43cc27c695e14a067429043c17` (Tag `3.0.1`). Der Upstream-Code wurde nicht verändert. Lizenz: GPL-3.0, siehe LICENSE im Quellarchiv.

Unter Debian 13 gebaut, mit System-libcurl und System-OpenSSL. Alle 17 Testausführungen erfolgreich; Programmstart und APT-Installationssimulation geprüft. Ein echter Upload/Download wurde nicht getestet.

Neubau: Quellarchiv entpacken und `packaging/README.Debian` beachten.
