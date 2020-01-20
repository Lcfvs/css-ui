# [css-ui](../../../#readme)/[components](../../#readme)/[menu](../#readme)/<a>mini</a>

## CDN

```html
<link href="https://unpkg.com/@lcf.vs/css-ui@3.0.1/css-ui/components/menu/mini/mini.min.css" media="screen" rel="stylesheet" /> 
```

## Usage

**Each `<a>` requires a `tabindex`!**

The menu must match `body > header + nav` containing:

```html
<a href="javascript:" tabindex="1">☰</a>
<a href="javascript:" tabindex="-1">⬅</a>
<ol>
    <li><a href="/">Home</a></li>
</ol>
```
