# Node-app
Objectifs :
- Développer une application web avec server-side rendering (SSR)
- Rendre du contenu HTML statique puis dynamique à l’aide de templates “mustache”
- Interroger des APIs externes avec les modules “http” (fourni) et “request”
- Initier et persister des sessions utilisateur avec le module “passport”

## Clone

```
$ git clone "insérer l'URL de votre dépôt distant ici"
$ cd node-app
$ npm use 12.15
```

## Générer une application web

```
$ npx express-generator --hogan --git
$ git add .
$ git commit -m "initial commit: express-generator"
$ git push 
```

## Installation
```
$ npm install
$ npm start
```
## Tester serveur
```
#le serveur doit être en cours d'execution
```

## Heroku : Connexion + envoi
```
$ heroku login 
$ heroku create 
$ git push heroku master
```
## Heroku : Lancement
```
$ heroku open
```
