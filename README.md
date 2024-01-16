# UCA Board

## Summary

- [French](#french)
- [English](#english)
- [License](LICENSE)

## French

- Cloner ou télécharger le dépôt
- Copier le dossier `libraries` dans le dossier `Arduino` de votre ordinateur (généralement `C:\Users\%USERNAME%\Documents\Arduino`)
- Ouvrir Arduino IDE
- Aller dans `File > Preferences > Additional Boards Manager URLs` et ajouter l'URL suivante : <https://raw.githubusercontent.com/ethandudu/UCA-Board/main/package_rfthings-avr_index.json>
- Aller dans `Tools > Board > Boards Manager ...`, rechercher `Arduino AVR Boards (RFThings)` par `RFThings Vietnam` et installer la dernière version
- Aller dans `Tools > Board > Arduino AVR Boards (RFThings)` et sélectionner `RFThings UCA`.
- Aller dans `Tools > Board Version` et sélectionner `3.9 and newer (ATMega328PB)`
- Aller dans `Tools > Programmer` et sélectionner `AVRISP mkII`
- Aller dans `Tools > Port` et sélectionner le port sur lequel est branchée la carte

Vous êtes prêt à programmer la carte !

## English

- Clone or download the repository
- Copy the `libraries` folder into the `Arduino` folder of your computer (usually `C:\Users\%USERNAME%\Documents\Arduino`)
- Open Arduino IDE
- Go to `File > Preferences > Additional Boards Manager URLs` and add the following URL: <https://raw.githubusercontent.com/ethandudu/UCA-Board/main/package_rfthings-avr_index.json>
- Go to `Tools > Board > Boards Manager ...`, search for `Arduino AVR Boards (RFThings)` by `RFThings Vietnam` and install the latest version
- Go to `Tools > Board > Arduino AVR Boards (RFThings)` and select `RFThings UCA`.
- Go to `Tools > Board Version` and select `3.9 and newer (ATMega328PB)`
- Go to `Tools > Programmer` and select `AVRISP mkII`
- Go to `Tools > Port` and select the port on which the board is plugged in

You are ready to program the board!

## License

All rights reserved by Université Côte d'Azur
