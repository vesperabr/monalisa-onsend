This Monalisa plugin prevent a form button to be clicked twice and show a nice loader when it was clicked.

## Installation

### NPM
```
npm install @vesperabr/monalisa-onsend
```

You also can download this repository and manually load the files in your project.

## Usage

Just put `data-component="onsend"` attribute in your button element.

You can customize the text that will appear after button's click. Just add the `data-text="Enviando"` attribute.

```html
<form>
    <button type="submit" data-component="onsend" data-text="Enviando">Enviar</button>
</form>
```

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
