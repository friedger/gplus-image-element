# &lt;gplus-image&gt;

Web Component wrapper for Google Plus image using Polymer.

> Maintained by [Filipe Barros](https://github.com/barrosfilipe).

## Demo

> [Check it live](http://barrosfilipe.github.io/gplus-image-element).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/polymer.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/gplus-image.html">
	```

3. Start using it!

	```html
	<gplus-image userid="109521309701815746194" size="120"></gplus-image>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`userid`   | *string*                  | ``                  | Gplus user id
`size`     | `normal`, `original` 	   | `normal`            | Image's dimension 

### Dimensions by `size` option

Size 		| Width
---			| ---
normal		| 120
original 	| 0


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* [v0.1.0](https://github.com/barrosfilipe/gplus-image-element/releases/v0.1.0) February 12, 2014
	* Released first version of gplus image element
* v0.1.1 February 5, 2014
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)
