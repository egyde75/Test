# Commandes Unix
## 1. Basics
```ls``` contenu d'un dossier  
```ls --size Data``` ou ```ls -s Data``` taille des fichiers du dossier  
```ls -sh Data``` idem en format 'human readable'  
```man ls``` accès au manuel, ```q```pour exit  
```h```ou ```help``` ou ```-help``` après une commande : aide sur la commande  
```.``` désigne le dossier actuel  
```..``` désigne le dossier parent  
```cd``` changer de dossier  
```pwd``` chemin du dossier actuel  
```~``` Home directory  
```tree```voir l'arborescence du dossier dans lequel je suis  
```tree + chemin d'un dossier```voir l'arborescence d'un dossier
## 2. Manipulation de dossiers ou fichiers
```mkdir +nom``` make directory = créer un dossier  (et le nommer)  
```cp +chemin du fichier à copier +chemin/nom dans destination``` copier et renommer    
```cp -r +chemin du dossier à copier +chemin de l'emplacement de destination``` copier un dossier entier  
```mv +chemin du fichier à déplacer +chemin de destination/nom``` déplacer et renommer  
```rm +chemin fichier``` suprimer le fichier  
```rm -r +chemin dossier```supprimer le dossier  
## 3. Manipulation de données  
```cat +nom de fichier``` ouvrir le fichier  
### 3.1. Navigation dans le fichier  
```down``` ou ```enter``` descendre d'une ligne  
```up``` remonter d'une ligne  
```space``` descendre d'une page  
```b``` remonter d'une page  
```g``` aller au début du fichier  
```shift + g``` aller à la fin du fichier  
### 3.2. Recherche dans le fichier  
```less /données cherchées```  
```p```pour previous occurence  
```n```pour next occurence  
recherche en arrière : ```?``` au lieu de ```/```  
```q``` pour quitter la commande  
### 3.3. Affichage dans le fichier  
```head +nom du fichier```voir les 10 1ères lignes du fichier  
pour choisir un autre nombre de lignes : utiliser ```-n```  
```head -n 15 +nom du fichier``` voir les 15 1ères lignes du fichier  
```tail +nom du fichier```voir les 10 dernières lignes du fichier  
pour choisir un autre nombre de lignes : utiliser ```-n```  
```wc +nom du fichier``` nombre de lignes, nombre de mots, nombre de caractères du fichier  
utiliser ```-l```pour ne voir que le nombre de lignes : ```wc -l +nom du fichier```  
```grep mot fichier``` extrait les lignes contenant le mot recherché - la 1ère position est donnée par la 2ème colonne  
```grep -c mot fichier```nombre de lignes contenant le mot recherché  
```grep -n mot fichier```numéro de la 1ère ligne contenant le mot recherché  
```-v```au lieu de ```-c``` extrait les lignes ne contenant pas le mot recherché  
```cut -f 3 fichier``` extrait la 3ème colonne du fichier - possibilité d'en extraire plusieurs en utilisant "," ou "-"  

:heart:
