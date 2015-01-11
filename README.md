x-translate
============

See the [component page](http://tryggvi.me/x-translate) for more information.

## &lt;x-translate&gt;

## Installation
> bower install x-translate

## How to use

Supported translation methods:

#### Translate with an object

Translate the h1 element to Icelandic from definitions in an object.

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

#### JSON file translation

Translation with a JSON file.

html:
```html
<body>
  <x-translate use="IS.json"></x-translate>

  <h1 translate="HEADER"> English! </h1>
</body>
```

js:
```js
var translator = document.querySelector('x-translate');
translator.use('json');
});
```
