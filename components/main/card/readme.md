# [css-ui](../../../#readme)/[components](../../#readme)/[main](../#readme)/<a>card</a>

## CDN

```html
<link href="https://unpkg.com/@lcf.vs/css-ui@3.0.5/css-ui/components/main/card/card.min.css" media="screen" rel="stylesheet" /> 
```

## Usage

```html
<a href="...">
  <figure>
    <img src="..." />
    <figcaption>Image legend</figcaption>
  </figure>
</a>
```

## Custom style

```css
a > figure:first-child:last-child {
  height: 20em;
  width: 20em;
}

a > figure:first-child:last-child img {
  max-height: 17em; /* based on your max fig caption height */
}
```
