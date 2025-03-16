## Configuration de l'environnement

1. Installer Python si ce n'est pas encore  installé
2. Accéder au dossier principal décompressé depuis le terminal ou le CMD (Ceux qui sont sur Windows je vous conseille d’utiliser git bash mais si vous êtes habitués à autre utilisé donc ça)
3. Installer la librairie *virtualenv* qui vous permettra de configurer un environnement virtuel de travail pour le projet: \
`pip install virtualenv`
4. Ensuite créer l’environnement virtuel nommé _envtp1_ par exemple. Vous pouvez trouver un autre nom à ça: \
`virtualenv myenv` ou `venv myenv` ou `python -m venv myenv`
5. Activer l’environnement virtuel sur le dossier créé précédemment:\
*Pour Windows:* `source myenv/Scripts/activate`\
*Pour macOs et Linux:* `source myenv/bin/activate`
6. Dans l’environnement virtuel (toujours dans votre dossier de départ créé), installer *Streamlit*\
`pip install streamlit`
7. Installer ensuite les librairies suivantes:\
`pip install pandas`\
`pip install numpy`
8. Lancer votre application Streamlit:\
`streamlit run ahouanyizounabraham.py`

## Utilisation de l'application une fois lancée
- Pour la page INSERTION CSV, vous allez importer un fichier csv

<font color="red">NB: Vous devez respecter les colonnes et les index des fichiers CSV même si vous personnalisez le contenu</font>

Fait par Abraham Mahubèyi AHOUANYIZOUN