## TP 3 : CSS
### Exercice 
Vous devez reproduire à l'identique (taille, couleur, bordures, marges) la page fourni en pièce jointe. 

Le site doit être déployé en ligne.

Vous êtes libres de choisir la police soit : 
 * en utilisant l'une des polices que aimez bien utiliser (les meme que votre suite bureautique office ou autre)
 
 ```
  html {
      font-family: Arial, Helvetica, sans-serif;
  }
 ```
 
 * en la téléchargeant sur votre projet => https://developer.mozilla.org/fr/docs/Web/CSS/@font-face
 * en faisant un import => https://fonts.google.com avec la balise <link>
  
Voici quelques indices : 
- Supprimer les marges(exterieur et interieur) par défauts avec le selecteur universel `*` 
    ``` 
    * {
         margin: 0;
         padding: 0;
     } 
    ```
- Télécharger une image en grand format au format paysage pour votre fond ecran sur https://www.pexels.com/fr-fr/
- L'élément qui à une image de fond doit faire en hauteur 95% de la fenetre. 
- Définissez votre dégradé avec une transparence à l'aide du site https://cssgradient.io/ 
    - Sinon vous pouvez utiliser ce dégradé superposé avec votre image sur le selecteur adequat
    ``` 
    background: linear-gradient(to right bottom, rgba(0, 0, 0, 0.4), rgba(250, 250, 250, 0.7)), **url(chemin-image)**;
    ```` 
    - En savoir plus sur les dégradé: https://developer.mozilla.org/fr/docs/Web/CSS/gradient/linear-gradient
- Positionnez vos textes en plein milieu de votre écran
    - [Centrer partement en CSS en position absolue](https://youtu.be/2JMx1cs2ir4) 
- Le document HTML doit être valide W3C : https://validator.w3.org/
- Le CSS doit être valide W3C : https://jigsaw.w3.org/css-validator/
- Pour obtenir votre parraléllogramme, utiliser le site : https://bennettfeely.com/clippy/ afin de coller votre propriété clip-path

![Example](images/demo.jpg)


## Modèle de départ CSS

Vous pouvez partir de ce modèle
```css
* {
    margin: 0;
    padding: 0;
}

html {
    font-family: /* Merci de completer */;
    /* Merci de completer */
}

header {
    background: /* Merci de completer */
    background-position: top;
    background-size: cover;
    /* Merci de completer */
}

h1 {
    position: absolute;
     /* Merci de completer */
}

h2  {
    position: absolute;
    /* Merci de completer */
}
```


## Ressources d'aide
- [Centrer en position absolue](https://youtu.be/2JMx1cs2ir4)
- https://developer.mozilla.org/fr/docs/Web/CSS/background
- https://developer.mozilla.org/fr/docs/Web/CSS/background-size
- https://developer.mozilla.org/fr/docs/Web/CSS/background-position
- https://developer.mozilla.org/fr/docs/Web/CSS/gradient/linear-gradient
- https://developer.mozilla.org/fr/docs/Web/CSS/letter-spacing
- https://developer.mozilla.org/fr/docs/Web/CSS/clip-path

