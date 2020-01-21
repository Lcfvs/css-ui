# css-ui
[![npm](https://img.shields.io/npm/v/@lcf.vs/css-ui.svg?style=plastic)](https://www.npmjs.com/package/@lcf.vs/css-ui)
[![Downloads](https://img.shields.io/npm/dt/@lcf.vs/css-ui.svg?style=plastic)](https://www.npmjs.com/package/@lcf.vs/css-ui)

A pure CSS base to make a responsive user interface.

* Accessible
* Flexible
* Classes/ids non-dependant
* No JavaScript required
* No non-semantic tags
* No hacks
* No browser specific media queries
* Easy to install

[Demo](https://lcfvs.github.io/css-ui/)


## Install

### Using NPM
`npm install @lcf.vs/css-ui --prefix site-dir/assets/css`

### Using a CDN
```html
<link href="https://unpkg.com/@lcf.vs/css-ui@3.0.7/css-ui.min.css" media="screen" rel="stylesheet" /> 
```

```html
<!DOCTYPE html>
<html lang="fr">
    <head>
        <meta charset="UTF-8">
        <title>Basic layout - css-ui</title>
        <link href="assets/css/variables.css" media="screen" rel="stylesheet" />
        <link href="https://unpkg.com/@lcf.vs/css-ui@3.0.7/css-ui.min.css" media="screen" rel="stylesheet" />
        <link href="https://unpkg.com/@lcf.vs/css-ui@3.0.7/components/menu/mini/mini.min.css" media="screen" rel="stylesheet" />
        <link href="https://unpkg.com/@lcf.vs/css-ui@3.0.7/components/header/popdown/popdown.min.css" media="screen" rel="stylesheet" />
        <link href="assets/css/style.css" media="screen" rel="stylesheet" />
        <meta name="viewport" content="width=device-width,initial-scale=1,shrink-to-fit=no" />
    </head>
    <body>
        <header>
            <h1>css-ui</h1>
        </header>
        <main>
            <h1>css-ui basic layout</h1>
            <section>
                <h1>Section title</h1>
                <p>Section content</p>
            </section>
        </main>
        <nav>
            <!--googleoff: anchor-->
            <a href="javascript:" tabindex="1">☰</a>
            <a href="javascript:" tabindex="-1">⬅</a>
            <!--googleon: anchor-->
            <ol>
                <li><a href="/">Home</a></li>
            </ol>
        </nav>
    </body>
</html>
```

## Variables

```css
:root {
  --css-ui--bg: /* rgba(245, 245, 255, 1) */;
  --css-ui--font: /* OpenSans, "Lucida Sans Unicode", "Lucida Grande", sans-serif */;
  --css-ui--padding: /* .5em */;
  --css-ui--contents-width: /* 20em */;
  --css-ui--header-bg: /* rgba(204, 204, 255, 1) */;
  --css-ui--header-height: /* 3em */;
  --css-ui--header--popdown-color: /* rgba(245, 245, 255, 1) */;
  --css-ui--header--popdown-width: /* 15em */;
  --css-ui--header--popdown-counter-color: /* rgba(255, 255, 255, .8) */;
  --css-ui--header--popdown-counter-bg: /* rgba(255, 0, 0, 1) */;
  --css-ui--header--popdown-counter-font-size: /* .8em */;
  --css-ui--header--popdown-counter-padding: /* .3em */;
  --css-ui--header--popdown-item-bg: /* rgba(255, 255, 181, 1) */;
  --css-ui--menu--bg: /* rgba(0, 0, 34, 1) */;
  --css-ui--menu--border: /* .063em solid rgba(255, 255, 255, .3) */;
  --css-ui--menu--color: /* rgba(204, 204, 255, 1) */;
  --css-ui--menu--icon-font: /* FontAwesome5Free */;
  --css-ui--menu--icon-size: /* 3em */;
  --css-ui--menu--height: /* 100% */;
  --css-ui--menu--overlay-bg: /* rgba(0, 0, 0, .3) */;
  --css-ui--menu--width: /* 15em */;
}
```


## Components

[Components](./components/#readme)

## License

[MIT](https://github.com/Lcfvs/css-ui/blob/master/licence.md)


## Contributions

A special thanks to [ascito](https://github.com/ascito) for some improvements. =)


## Compatibility

* PC
    * Firefox
    * Chrome
    * Edge
    * Opera
    * Yandex

* Mobile
    * Firefox
    * Chrome
    * Safari
    * Samsung
    * UC Browser
    
* Mac
    * Firefox
    * Safari
    * Chrome
    * Opera

All the compatibility tests are made on [<img height="36px" src="./Browserstack-logo.svg" />](https://www.browserstack.com)
