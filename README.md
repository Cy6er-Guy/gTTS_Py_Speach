
```markdown
# Application Flask de Génération de Speech

Cette application web Flask permet de convertir du texte en speech audio dans différentes langues en utilisant le module gTTS (Google Text-to-Speech).

## Fonctionnalités

- Saisir du texte à convertir en speech.
- Sélectionner la langue souhaitée pour le speech.
- Télécharger le fichier audio généré.
- Chaque fichier audio généré a un nom unique basé sur un UUID.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé les outils suivants :

- Python (version 3.x recommandée)
- Flask
- gTTS (Google Text-to-Speech)

Vous pouvez installer Flask et gTTS en utilisant pip :

```bash
pip install flask gtts
```

## Comment utiliser

1. **Cloner le dépôt**

   Clonez ce dépôt sur votre machine locale :

   ```bash
   git clone https://github.com/Cy6er-Guy/gTTS_Py_Speach.git
   cd speech_app
   ```

2. **Lancer l'application**

   Lancez l'application Flask en exécutant `app.py` :

   ```bash
   python app.py
   ```

   L'application sera accessible à l'adresse suivante : `http://localhost:5000` dans votre navigateur.

3. **Utiliser l'application**

   - Remplissez le champ "Texte à convertir" avec le texte de votre choix.
   - Sélectionnez la langue dans la liste déroulante "Langue".
   - Cliquez sur le bouton "Générer Speech".
   - Le fichier audio sera généré et un lien de téléchargement apparaîtra pour télécharger le fichier MP3.

## Structure des fichiers

- **`app.py`** : Contient le code principal de l'application Flask.
- **`templates/`** : Répertoire contenant les fichiers HTML pour l'interface utilisateur.
- **`static/`** : Répertoire contenant les fichiers statiques tels que le CSS et les scripts JavaScript.

## Auteur

- Cy6er_Guy
