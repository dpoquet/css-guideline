# css-guideline
CSS Guideline - Buenas prácticas

```scss
.spots-list {
  padding: 0;
  margin: 0;

  .spots-list__item {
    padding-left: 90px;

    .spots-list__item__icon {
      display: block;
      position: absolute;
      top: 0;
      left: 0;
      width: 80px;
      height: 80px;
    }

    .spots-list__item__min {
      display: block;
      @include font-size(25);
      font-weight: 600;

      > span {
        @include font-size(40);
      }
    }

    .spots-list__item__name {
      display: block;
      @include font-size(17);
    }

  }

}

``` 
