x-translate
============

See the [component page](tryggvigy.github.io/x-translate) for more information.

## &lt;x-translate&gt;

## Installation
> bower install x-translate

## How to use

The code below translates the h1 element to Icelandic.

html:
```html
<body>
  <x-translate></x-translate>

  <h1 translate="HEADER"> English! </h1>
</body>
```

js:
```js
var langIS = {
  HEADER : "Íslenska!"
}

var translator = document.querySelector('x-translate');
translator.use(langIS);
});
```
