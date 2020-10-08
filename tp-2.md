## TP 2 : CSS
### Exercice 1 : Dynamiser vos mises en page

Dans cet atelier, vous constaterez qu'une simple régle rendra votre mise ne page dynamique (elle s'adaptera à l'interface de l'utilisateur)

- Faites en sorte que chaque diviseur occupe 80% de son conteneur. 
- Affectez-leur ensuite des dimensisons minimales et maximales (dans notre exemple 250 et 750 pixels)

```css
html, body {
    padding: 0,
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
