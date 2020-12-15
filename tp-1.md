## TP 1 : CSS 

Merci de vous créer un compte https://jsbin.com pour faire les exercices suivants et sauvegarder votre travail avant de l'envoyer.
6 liens sont attendus


### Exercice 1 : Modifier la taille de la police

Dans le code suivant :
  - Faites-en sorte que la taille du texte des liens soit de 12px.
  - Le texte des balises p et strong devra quant à lui faire 16px.
```html
<p>Le contenu de <a href="#"> notre paragraphe</a>: Voici le contenu de notre paragraphe 
    <a href="#">avec une ancre contenant<strong> une forte emphase de texte</strong></a>. 
    Nous pouvons ajouter un peu de texte afin de prolonger un peu le plaisir.
</p>
```
### Exercice 2 : Sélectionner les descendants 

Dans le code suivant :
   - Réduiser la taille du texte du lien contenu dans la balise div à 75% de sa taille héritée.
   - Augmenter celle du lien contenu dans la seconde balise p à 150% de sa taille originale.
```html
<div> 
  <p> Ce paragraphe contient <a href="#">un premier lien</a></p>
</div>
<p> Ce paragraphe contient <a href="#">un second lien</a></p>
```

### Exercice 3 : Sélectionner des classes

Dans le code suivant :
   - Appliquez un texte gras aux classes important. Si la classe est appliquée à un lien, mettez le en italique.
```html
<h1>Mon titre</h1>
<div>
    <p>Ceci est mon paragraphe avec un lien <a class="important" href="#"> un premier lien</a></p>
</div> 
<p class="important">
    Ceci est mon deuxième paragraphe <a href="#">un second lien<a>
</p> 
```


### Exercice 4 : Sélectionner des identifiants

Dans le code suivant :
   - Faites en sorte que les paragraphes contenus dans la balise div qui possède l'id contenu soit en gras.
   - Mettez le paragraphe qui possède l'id important en italique et en gras.
```html
<h1>Sélectionner des identifiants</h1>
<div id="contenu">
   Ce texte n'appartient pas au paragraphe inclut dans #contenu.
   <p> Ce paragraphe contient <a href="#"> un  premier lien </a></p>
</div>
<p id="important">
   Ce paragraphe contient <a href="#"> un second lien</a>. 
</p>
```

### Exercice 5 : Selectionner des pseudos-classes et pseudo-elements

Dans le code suivant :
- Faites en sorte que la premiere lettre du titre fasse deux fois la taille du texte courant.
- Changez le premier lien de chaque paragraphe en italique. Quand l'utilisateur survole un lien, il doit s'afficher de nouveau sans italique.
- Quand le champ input de type text a le focus, sa couleur de fond doit devenir jaune. 
Si l'utilisateur survole le bouton (input de type submit), sa couleur de fond doit devenir noire et celle du texte blanc.

```html
<h1>Selectionner des pseudos-classes et pseudo elements</h1>
<p>Appliquons ensemble <a href="#"> La thérorie des selecteurs </a></p>
    <form action="#">
        <div>
            <label for="texte">Mettez votre texte : </label>
            <input type="text" id="texte" value="mon champ">
            <input type="submit" text="Cliquez ici">
        </div>
    </form>
    <p>Ce paragraphe contient deux liens : 
      <a href="#">un premier lien</a> et
      <a href="#">un second lien</a>
    </p>
``` 

### Exercice 6 : Selectionner des pseudos-classes et pseudo-elements
Dans le code suivant :
- Appliquez une police de votre choix 1.5 fois plus grande que celle du navigateur, 
    sachant que la taille par défaut a été modifié à 18px;
- La section doit faire 95% de la hauteur de la fenetre
- A la sélèction du texte du document, le fond doit être noir et le texte en blanc
```html
<section>
    <h1> Steve Jobs </h1>
    <p>Début 1997, Apple, alors au bord de la faillite, rachète NeXT. 
    L'opération permet à Steve Jobs de revenir à la tête de la firme 
    qu'il a cofondée et fournit à Apple le code source de NeXTSTEP 
    à partir duquel est développé le système d'exploitation Mac OS X.
    </p>
</section>

```
