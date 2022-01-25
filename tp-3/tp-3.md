## TP 3 : CSS
### Exercice 
Vous devez reproduire à l'identique (taille, couleur, bordures, marges) la page fourni en pièce jointe. 

Le site doit être déployé en ligne.

Vous êtes libres de choisir la police soit : 
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
- Télécharger une image au hasard pour votre fond ecran sur https://www.pexels.com/fr-fr/
- L'élément qui à une image de fond doit faire en hauteur 95% de la fenetre. 
- Définissez votre dégradé avec une transparence à l'aide du site https://cssgradient.io/ 
    - Sinon vous pouvez utiliser ce dégradé superposé avec votre image sur le selecteur adequat
    ``` 
    background: linear-gradient(to right bottom, rgba(0, 0, 0, 0.4), rgba(250, 250, 250, 0.7)), url(chemin-image);
    ```` 
- Le document HTML doit être valide W3C : https://validator.w3.org/
- Le CSS doit être valide W3C : https://jigsaw.w3.org/css-validator/
- Pour obtenir votre parraléllogramme, utiliser le site : https://bennettfeely.com/clippy/ afin de coller votre propriété clip-path

![Example](images/demo.jpg)

## Ressources d'aide
- [Centrer en position absolue](https://youtu.be/2JMx1cs2ir4)

- https://developer.mozilla.org/en-US/docs/Web/CSS/background

- https://developer.mozilla.org/en-US/docs/Web/CSS/background-size

- https://developer.mozilla.org/en-US/docs/Web/CSS/background-position

