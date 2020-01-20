# [css-ui](../../../#readme)/[components](../../#readme)/[header](../#readme)/<a>popdown</a>

## CDN

```html
<link href="https://unpkg.com/@lcf.vs/css-ui@2.4.4/css-ui/components/header/popdown/popdown.min.css" media="screen" rel="stylesheet" /> 
```

## Usage

**Each `<a>` requires a `tabindex`!**

The popdown container must match `body > header > ol`, containing one of the following:


### Simple button

```html
<li>
    <a aria-label="Logout" href="#logout" role="button" tabindex="99996"></a>
</li>
```

### Countable list
```html
<li>
    <a aria-label="Opener" href="javascript:" role="button" tabindex="99997"></a>
    <ol>
        <li><a href="#message-1">New message (1)</a></li>
        <li><a href="#message-2">New message (2)</a></li>
        <li><a href="#message-3">New message (3)</a></li>
        <li><a href="#message-4">New message (4)</a></li>
    </ol>
    <p>Default message, visible when the list is empty</p>
    <a aria-label="Closer" href="javascript:" role="button" tabindex="-2"></a>
</li>
```

### Empty countable list container (no counter)
```html
<li>
    <a aria-label="Opener" href="javascript:" role="button" tabindex="99998"></a>
    <p>Default message or notification</p>
    <a aria-label="Closer" href="javascript:" role="button" tabindex="-3"></a>
</li>
```
