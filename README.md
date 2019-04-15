# c'est quoi 

* GitBook est une plate-forme de documentation moderne où les équipes peuvent tout documenter 

* Gitbook peut etre utilisé pour créer un livre, une documentation publique, un manuel 
d'entreprise, une thèse, etc.


## Comment

* Instalation de gitbook depuis une image docker.

    Une image de docker gitbook pour vous permettre de construire et de publier votre documentation.


GitBook a besoin d’une table des matières qui pointe sur les différents fichiers markdown de votre futur ouvrage.

# Prérequis :

* ```gitbook``` avec option pdf grâce à calibre
* ```calibre``` requis par gitbook pour la génération de pdf
* ```npm``` requis pour gitbook
* ```lftp``` télécharger vos documents sur un site distant
* ```git``` pour obtenir votre source de doc
* ```node```
* ```grunt``` permet d’automatiser le processus de génération, mais aussi de publication vers une branche gh-pages du repository (accès  “site web”).
*```Github``` 


##  Usage

**Pour construire votre documentation dans un répertoire spécifique:**
```
docker run -v /my_gitbook:/gitbook amontaigu/gitbook gitbook build docs html
```

**Pour aller à l'intérieur du conteneur, jouez avec les commandes disponibles dans un shell:

**
```
docker run -it --rm --entrypoint=/bin/sh amontaigu/gitbook
```

## References

* https://www.gitbook.com/
* https://hub.docker.com/_/node/
* https://www.npmjs.com/package/gitbook
* https://www.npmjs.com/package/gitbook-cli
* https://github.com/Fellah/docker/blob/master/gitbook/Dockerfile
* https://toolchain.gitbook.com/syntax/asciidoc.html
* http://asciidoctor.org/docs/asciidoc-syntax-quick-reference/
* https://youtu.be/1rKgVF5CEEY
* https://calibre-ebook.com/download_linux
* https://toolchain.gitbook.com/ebook.html
