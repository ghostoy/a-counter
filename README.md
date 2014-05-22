# &lt;a-counter&gt;

Animated counter based on Polymer

> Maintained by [Cong Liu](https://github.com/ghostoy).

## Demo

> [Check it live](http://ghostoy.github.io/a-counter).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="bower_components/platform/platform.js"></script>
	```

2. Start using it!

	```html
	<a-counter></a-counter>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`value`    | *string*                  | `""`                | Value to display on the counter
`pattern`  | *string*				   | `"[0-9]{10}"`       | Pattern of the value in format of regular expression
`hold`     | *boolean*                 | `false`             | Hold the animation on loaded or after the value changed.
`animation`| *string*				   | `normal`			 | Speed of animation: slow (4s), normal (2s), fast (1s), super-fast (0.5s), none (no animation)

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History
* v0.0.2 May 22, 2014
	* Updated to bower version of Polymer 0.2.3
* v0.0.1 Nov 7, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)