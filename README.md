# GNU/Linux
Her finner du en samling med diverse shell skript jeg har laget for forskjellige formål, stort sett for å gjøre livet enklere.

## Fedora og Nvidia oppsett for gaming
Har du installert Fedora Workstation eller Fedora KDE Plasma Desktop og du har en maskin med Nvidia grafikkort? Isåfall har jeg [her laget et skript som installerer alt du måtte trenge av drivere og programvare](https://github.com/Gauteweb/GNU-Linux/blob/main/fedora_nvidia_gaming.sh) for å enkelt komme igang med gaming på Linux.

Sjekk også ut mine [rapporter på ProtonDB](https://www.protondb.com/users/440092954) for tweaking av individuelle spill på Fedora og SteamOS.

## Forenklet oppdatering av Fedora
Dette skriptet fungerer på alle varianter av Fedora og sannsynligvis også på alle Fedora-baserte distroer som for eksempel Bazzite og Nobara. [Skriptet oppdaterer både Flatpak og DNF i en swoop](https://github.com/Gauteweb/GNU-Linux/blob/main/update_fedora.sh). 

Jeg har satt det opp til å startes fra en knapp på min Stream Deck slik at oppdateringer alltid bare er et knappetrykk unna. Jeg ahr da brukt OpenDeck med "Run Command":
- KDE Plasma: konsole -e ./update.sh
- GNOME: terminal -e ./update.sh
