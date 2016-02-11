# Titles

As we started writing a markdown document, we need to add a title and some sub-headers.

Markdown supports two styles of headers, Setext and atx.

Setext-style headers are “underlined” using equal signs (for first-level headers) and dashes (for second-level headers). For example:

```
This is an H1
=============

This is an H2
-------------
```

Any number of underlining =’s or -’s will work.

Atx-style headers use 1-6 hash characters at the start of the line, corresponding to header levels 1-6. For example:

```
# This is an H1

## This is an H2

###### This is an H6
```


Optionally, you may “close” atx-style headers. This is purely cosmetic — you can use this if you think it looks better. The closing hashes don’t even need to match the number of hashes used to open the header. (The number of opening hashes determines the header level.) :

```
# This is an H1 #

## This is an H2 ##

### This is an H3 ######
```

Traduction française

#Titres

Quand nous commençons à écrire un document en markdown , nous avons besoin d'ajouter des titres et des sous titres.
Markdown suporte deux types d'entête , Setext et atx.
Les titre de style setext sont "sous ligné" en utilisant des signes égal (pour les titres de premier niveau) et par des tirets (pour les titres de second niveau). Par exemple :
```
ceci est un H1
==============
 
ceci est un h2
--------------
```
Le nombre d'egal ou de tiret qui souligne n'a pas d'importance.

Les titres de style atx utilise entre 1-6 dieses au début de la ligne, correspondant au niveau de titre 1-6 par exemple :
```m
# Ceci est un H1
## Ceci est un H2
###### Ceci est un H6
```
Optionnelement vous pouvez "fermer" les titres de style atx . Ceci est purement esthétique , vous pouvez l'utiliser si vous trouver que cela fait mieux.Le nombre de dieses a la fin n'a pas besoin d'être identique au nombre de dieses du début , c'est le nombre de dieses d'ouverture qui défini le niveau du titre.

```
# Ceci est un H1 #
## Ceci est un H2 ##
#### Ceci est un H4 ##########

---

Here's a quiz about markdown titles.

Select the valid headers:
- [x] `# hello`
- [ ] `#hello`

> Headers need space between the hash characters and the text.

Select the valid headers:
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Only '=' and '-' are accepted for underlining an header.

---


