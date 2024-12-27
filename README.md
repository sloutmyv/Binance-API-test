# Binance-API-test

doc : [Binance-python](https://python-binance.readthedocs.io/en/latest/overview.html)

## Langage de programation
Installer le langage [Python](https://www.python.org/downloads/)
## Editeur de texte
Installer l'éditeur [Visual studio](https://code.visualstudio.com/) 
## Github
Pour chaque nouveau projet créer un répertoire directement depuis le [GitHub](https://github.com/)

### Le fichier ".gitignore"
Il est créé à la racine du projet pour indiquer les fichier à ne pas upload sur le répertoire github en ligne, à inclure (pour un projet Django):
```
# Environments
.env
.venv
env/
venv/
ENV/
env.bak/
venv.bak/
```
## Environnement virtuel
Installer le package d’environnement virtuel : 
```
pip3 install virtualenv
```
Creer l’environnement virtuel : 
```
python3 -m venv <virtual-environnement-name>
```
Activer l’environnement virtuel : 
- Linux/Mac :
```
source <virtual-environnement-name>/bin/activate
```
Désactiver l’environnement virtuel :
``` 
deactivate
```
## Installer les Packages : 
```
pip install <some-dependance>
```
Lister les dépendances : 
```
pip freeze
```
Ajouter les dépendances à un fichier “requirement.txt”
```
pip freeze > requirement.txt
```
Installer les dépendances présentes dans un fichier “requirement.txt” : 
```
pip install -r requirement.txt
```
## Objectif(s)

+ Analyse du marché crypto 
> market cap / market cap evo 
> market deph 
> graph volume de transaction / capitalisation / volatilé pour les x plus grosse cap. 
> graph evolution relative des 10 plus grosse capitalisaiton
* Analyse de la composition du portefeuille binance 
* Comment placer un ordre 
> en spot 
> en marge  
* Faire des transfert entre portefeuille spot / marge / earn 
* Tracer un évolutif de la composition du portefeuille 

