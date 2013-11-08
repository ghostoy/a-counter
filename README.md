# &lt;a-counter&gt;

TODO: Write a project description

> Maintained by [Cong Liu](https://github.com/ghostoy).

## Demo

> [Check it live](http://ghostoy.github.io/a-counter).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20131025/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/a-counter.html">
	```

3. Start using it!

	```html
	<a-counter></a-counter>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`value`    | *int*                     | `0`                 | Value to display on the counter
`max-length`| *int*				 	   | `3`               	 | Max length in digits
`pre`      | *string*                  | `""`                | String to be displayed before the number
`post`     | *string*                  | `""`                | String to be displayed after the number
`hold`     | *boolean*                 | `false`             | Hold the animation on loaded or after the value changed.
`animation`| *string*				   | `normal`			 | Speed of animation: slow (4s), normal (2s), fast (1s)

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 Nov 7, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)