Réutilisation du repo officiel d'Elegoo : https://github.com/elegooofficial/ELEGOO-TumbllerV1.1-Self-Balancing-Car-Tutorial.
Adaptation du dossier pour platformio sous VSCode.


Sous VSCode, éditer le fichier c_cpp_properties.json et ajouter la ligne suivante dans la section includePath :
"user_path/Tumbller Self-Balancing Car/include",
... où user_path est le chemin vers le dossier contenant le projet.

Également, configurer platformio.ini pour utiliser le bon port série (voir la section [env:uno] du fichier).