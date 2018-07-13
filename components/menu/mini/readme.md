# [css-ui](../../../#readme)/[components](../../#readme)/[menu](../#readme)/<a>mini</a>

## CDN

```html
<link href="https://cdn.rawgit.com/Lcfvs/css-ui/2.4.1/css-ui/components/menu/mini/mini.min.css" media="screen" rel="stylesheet" /> 
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