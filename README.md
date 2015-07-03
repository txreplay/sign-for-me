# Sign4Me

## What is it ?

**Sign4Me** is a website to manage the students 

## How to install ?

### installation et dépendances
 
#### Node et le gestionnaire de paquet NPM

Vérifier la dispo des  commandes suivantes :

```JS
node -v
npm -v
```
 
Installer nodejs dans le cas contraire : http://nodejs.org/


#### Bower, Compass, Grunt
 
```JS
npm install -g bower
npm install -g compass
npm install -g grunt-cli
```

Note : argument "-g" met à disposition globalement la commande 

 
#### Install Ruby, Compass , imagemagick
  
[Ruby](http://www.ruby-lang.org/en/downloads/)
[Sass](http://sass-lang.com/tutorial.html)
[imagemagick](http://www.imagemagick.org/script/binary-releases.php#windows)
 
 
 
#### Récupération des dépendances JS/CSS
 
```JS
bower install (project directory)
```
 
Note : .bowerrc  surcharge les répertoires de destination par défaut

 
 
#### Récupération des dépendances Node
 
```JS
npm install
```
 
Note : charge les paquets dans "node_modules"



## Commandes Grunt

Lancer le serveur et scruter les changements :

```JS
grunt serve
```

Génération des sprites (retina compris) :

```JS
grunt sprites
```

Lancer un test:

```JS
grunt test
```

## Mise en prod

- step 1/2 :

```JS
grunt build
```
- step 2/2 :

Copier le dossier dist sur le serveur

## Tests

## Team

Bachelors Hetic - WEB2 :

* Emmanuel Gorre
* Antoni Ortega
* Valentin Commenge
* Johnatan Simonet
* Giovanny Pied