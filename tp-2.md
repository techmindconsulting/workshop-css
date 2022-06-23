## TP 2 : CSS

A faire sur codepen

## Remarque

Faites une recherche google pour toute propriété que ne comprenez pas.

### Exercice 1 : Dynamiser vos mises en page

Dans cet exercice, vous constaterez qu'une simple régle rendra votre mise en page dynamique (elle s'adaptera à l'interface de l'utilisateur)

- Faites en sorte que chaque diviseur occupe 80% de son conteneur. 
- Affectez-leur ensuite des dimensions minimales et maximales (dans notre exemple 250 et 750 pixels)

#### Liens utiles

* https://developer.mozilla.org/en-US/docs/Web/CSS/width
* https://developer.mozilla.org/fr/docs/Web/CSS/max-width
* https://developer.mozilla.org/fr/docs/Web/CSS/min-width
* https://developer.mozilla.org/fr/docs/Web/CSS/height
* https://developer.mozilla.org/fr/docs/Web/CSS/max-height
* https://developer.mozilla.org/fr/docs/Web/CSS/min-height

```css
html, body {
    padding: 0;
    margin: 0;
    width: 100%;
    height: 100%;
}
div {
    border: solid 1px #000;
    background-color: #eee;
    color: #555;
}
div div {
    margin: 5px;
}
```

```html
  <div>
    Voici un peu de texte...
    <div>
      ...qui va continuer dans ce diviseur...
      <div>
        ...passer par celui-ci...
        <div>
          ...pour finir par la...
        </div>
      </div>
    </div>
  </div>
```
### Exercice 2 : Créer un menu verticale

<img src="tp-2-exo-2-img-1.jpg" alt="demo exo tp-2">

Vous allez utiliser une liste afin de créer un menu de navigation. 
- Il faudra que les ancres `<a>` occupent l'intégralité de l'item qui les contient, afin que la zone "cliquable" ne se limite pas au texte. 
- Augmenter la taille des zones "cliquables" permettra notamment une meilleure accessibilité.

#### Liens utiles

* https://developer.mozilla.org/en-US/docs/Web/CSS/width
* https://developer.mozilla.org/fr/docs/Web/CSS/max-width
* https://developer.mozilla.org/fr/docs/Web/CSS/min-width
* https://developer.mozilla.org/fr/docs/Web/CSS/height
* https://developer.mozilla.org/fr/docs/Web/CSS/max-height
* https://developer.mozilla.org/fr/docs/Web/CSS/min-height


```css
ul {
    width: 150px;
    padding: 0;
    margin: 0;
    list-style-type: none;
    border: solid 1px #000;
    font: 1rem Impact, Arial, Helvetica, sans-serif;
    text-transform: uppercase;
}
    
li {
    line-height: 3rem;
    text-align: center;
}
    
a { 
  height: 3rem;
  text-decoration: none;
  background-color: #eee;
  color: #555;
}

a:hover {
 /*  Merci de compléter */ 
}
```

```html
  <ul>
    <li><a>Presentation</a></li>
    <li><a>Service</a></li>
    <li><a>Contact</a></li>
    <li><a>Espace client</a></li>
  </ul>
```

### Exercice 3 : Créer un menu horizontale

<img src="tp-2-exo-3-img-1.jpg" alt="demo exo tp-3">

- Reprenez l'exercice précédent afin de faire un menu horizontale

#### Liens utiles
* https://developer.mozilla.org/fr/docs/Learn/CSS/Building_blocks/The_box_model#le_positionnement_display_inline-block
* https://youtu.be/j2HWn2G1R4A

### Exercice 4 : Positionnez des boîtes
Dans cet exercice
- Positionner les différents blocs div à l'aide de top et left de telle sorte qu'il forme la figure suivante. Les blocs font 200 pixels de largeur et de hauteur avec 2 pixels de bodure et 0.5rem de padding

#### Liens utiles
* https://developer.mozilla.org/fr/docs/Learn/CSS/CSS_layout/Positioning#positionnement_absolu
* https://developer.mozilla.org/en-US/docs/Web/CSS/z-index
* https://youtu.be/CJIzLfXgtMM
* https://youtu.be/dqoVhIxHhLU

![blocs de 200 pixels](https://github.com/techmindconsulting/workshop-css/blob/main/tp-2-exo-4-img-1.jpg)

- Grace à un z-index, placez le bloc de l'id div1 au dessus des autres. Vous devriez obtenir ceci

![blocs de 200 pixels](https://github.com/techmindconsulting/workshop-css/blob/main/tp-2-exo-4-img-2.jpg)

```html
  <div id="div1">Bloc 1</div>
  <div id="div2">Bloc 2</div>
  <div id="div3">Bloc 3</div>
  <div id="div4">Bloc 4</div>
  <div id="div5">Bloc 5</div>
```

```css
div {
  background-color: skyblue;
  color: white;
  font: bold 0.8em Arial, Helvetica, sans-serif
}

#div1 {
  border-color: #fff;
}
#div2 {
}
#div3 {
}
#div4 {
}
#div5 {
}
```

