# game-character

The take on @una's game characters (from 2017 CSS Conf talk)  as a web component (native) with CSS3 custom properties instead of SCSS.

![image](https://user-images.githubusercontent.com/14539/28441004-ef1d56ca-6da8-11e7-9db9-617b693042a7.png)

## Usage

### Game character with pixel map and colour map definition

```html
<game-character id="mario">
  <pixels>
      (o o o r r r r r r o o o o)
      (o o r r r r r r r r r r o)
      (o o t t t p p p k p o o o)
      (o t p t p p p p k p p p o)
      (o t p t t p p p p k p p p)
      (o t t p p p p p k k k k o)
      (o o o p p p p p p p p o o)
      (o o r r b r r r r o o o o)
      (o r r r b r r b r r r r o)
      (r r r r b b b b r r r r o)
      (p p r b y b b y b r p p o)
      (p p p b b b b b b p p p o)
      (p p b b b b b b b b p p o)
      (o o b b b o o b b b o o o)
      (o t t t o o o o t t t o o)
      (t t t t o o o o t t t t o)
  </pixels>
  <colors>
    'r': #f00,
    'w': #fff,
    'k': #000,
    "o": transparent,
    't': #83401f,
    'p': #ffbc77,
    'b': #06f,
    'y': #ff0,
    'n': #ff8000,
    'g': #5ac528
  </colors>
</game-character>
```

### Game character with pixel map definition and default colour palette

```html
<game-character id="star">
  <pixels>
      (o o o o o o o k k o o o o o o o)
      (o o o o o o k y y k o o o o o o)
      (o o o o o o k y y k o o o o o o)
      (o o o o o k y y y y k o o o o o)
      (k k k k k k y y y y k k k k k k)
      (k y y y y y y y y y y y y y y k)
      (o k y y y y k y y k y y y y k o)
      (o o k y y y k y y k y y y k o o)
      (o o o k y y k y y k y y k o o o)
      (o o o k y y y y y y y y k o o o)
      (o o k y y y y y y y y y y k o o)
      (o o k y y y y y y y y y y k o o)
      (o k y y y y y k k y y y y y k o)
      (o k y y y k k o o k k y y y k o)
      (k y y k k o o o o o o k k y y k)
      (k k k o o o o o o o o o o k k k)
  </pixels>
</game-character>
```

## Author

@peterblazejewicz
