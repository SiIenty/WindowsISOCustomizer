CustomWindowsISO.ps1
====================

Description :
-------------
Ce script PowerShell permet de créer une image ISO personnalisée de Windows.
Il automatise des étapes telles que l'intégration de mises à jour, de pilotes, la suppression de composants inutiles, et l'application de personnalisations système.

Fonctionnalités :
-----------------
- Montage d'une image Windows (WIM)
- Intégration de fichiers ou de scripts dans l'image
- Nettoyage des composants superflus
- Création d'une nouvelle ISO bootable personnalisée

Prérequis :
-----------
- Windows 10 ou supérieur
- PowerShell en mode administrateur
- Outils DISM et oscdimg disponibles dans le système

Utilisation :
-------------
1. Placez l’ISO originale de Windows dans le dossier indiqué par le script.
2. Exécutez le script PowerShell en tant qu'administrateur :
   `.\CustomWindowsISO.ps1`
3. Suivez les instructions affichées dans le terminal.

Remarques :
-----------
- Il est recommandé de tester l’image personnalisée dans une machine virtuelle avant de l’utiliser sur une machine physique.
- Modifiez le script selon vos besoins pour intégrer des personnalisations spécifiques (clé de registre, apps, etc.)

Auteur :
--------
Silenty - 2025
