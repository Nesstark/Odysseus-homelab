# Status

## Aktiv fase
Fase A — Stabilisering og Linux-fundament

## Denne uges mål
Kortlæg Odysseus sikkert og forstå systemets vigtigste komponenter uden at foretage ændringer.

## Bekræftet hardware
- ASUS ZenBook UX434DA/UM433DA
- AMD Ryzen 7 3700U, 4 kerner / 8 tråde
- Cirka 6 GiB RAM og 6 GiB swap
- 477 GB NVMe
- 1 TB SATA-disk monteret på `/mnt/toshiba`

## Bekræftet software og tjenester
- Debian GNU/Linux 13 “Trixie”
- Linux-kernel 6.12
- Docker
- Immich
- Tailscale

## Adgangsmodel
- Immich og serveradministration skal forblive private via Tailscale.
- Ingen offentlig eksponering er planlagt i de første faser.

## Senest afsluttet
- Headless Debian-server etableret
- Docker og Immich sat i drift
- Privat adgang etableret via Tailscale
- Grundlæggende hardware- og OS-information indsamlet

## Åbne spørgsmål
- Hvor ligger Immichs upload-bibliotek og PostgreSQL-data?
- Hvor ligger Compose- og miljøfilerne?
- Hvilke Docker-volumes, bind mounts og netværk bruges?
- Hvilke filsystemer anvendes, og hvor meget plads er ledig?
- Findes der allerede en backup eller restore-procedure?
- Hvilke services, sockets og porte lytter på hvilke interfaces?

## Næste handling
Kortlæg host, storage, systemd, Docker og Immich med read-only kommandoer og et share-safe check.

## Seneste verificering
- Dato:
- Test:
- Resultat: