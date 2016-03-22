##CSS Guideline - Buenas prácticas

### Nomenclatura
Utilizo la metedología BEM para realizar la nomenclatura CSS:
```css
    .bloque{}
    .bloque__elemento{}
    .bloque--modificador{}
```

Una claro ejemplo del funcionamiento con BEM sería:
```css
    .spots-list{}
    .spots-list--big{}
    .spots-list--small{}
        .spots-list__item{}
        .spots-list__item--active{}
``` 

### Disposición del código SCSS
