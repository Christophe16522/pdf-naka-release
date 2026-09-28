# PDF Naka

Outil Windows pour modifier, fusionner, diviser, convertir, signer et compresser des PDF.
Tout se passe sur votre ordinateur : aucun fichier n'est envoyé sur Internet.

Ce dépôt ne contient que les versions à télécharger. Le code source est privé.

## Télécharger

Dernière version : [Releases](https://github.com/Christophe16522/pdf-naka-release/releases/latest)

| Fichier | Usage |
| --- | --- |
| `PDFNaka-Setup-x.y.z.exe` | Installateur (recommandé). Aucun droit administrateur requis, raccourci dans le menu Démarrer, désinstallation propre, mise à jour en place. |
| `PDFNaka-windows.zip` | Version portable : décompressez le dossier et lancez `PDFNaka.exe`. |

Prérequis : Windows 10 ou 11, 64 bits. Les conversions Word, Excel et PowerPoint vers PDF utilisent Microsoft Office s'il est installé sur le poste.

## Premier lancement

L'exécutable n'est pas encore signé : Windows SmartScreen peut afficher un avertissement.
Cliquez sur « Informations complémentaires », puis « Exécuter quand même ».

## Installation silencieuse (déploiement par script)

```
PDFNaka-Setup-x.y.z.exe /VERYSILENT /NORESTART /SUPPRESSMSGBOXES
```

## Mises à jour

L'application vérifie au démarrage si une version plus récente est disponible ici et propose de la télécharger.

## Fonctions

| Famille | Outils |
| --- | --- |
| Organiser | Fusionner, diviser, pivoter, rogner, réordonner, extraire, insérer une page vierge |
| Modifier | Texte existant, ajout de texte, images, signature, surlignage, formes, dessin, formulaires, filigrane, compression, métadonnées, aplatir, guides d'alignement |
| Convertir | PDF ⇄ Word, PDF ⇄ Excel, PDF ⇄ PowerPoint, PDF ⇄ JPG/PNG |
| Sécurité | Mot de passe, déverrouillage, effacement des métadonnées |
| OCR | Reconnaissance de texte sur les scans, export du texte |

## Signaler un problème

Ouvrez une [issue](https://github.com/Christophe16522/pdf-naka-release/issues) en précisant la version (affichée en bas de l'application) et les étapes pour reproduire.

© Christophe Lai. Tous droits réservés.
