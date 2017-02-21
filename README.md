# &lt;juicy-input&gt;

`<juicy-input>` Custom Element that highlights input fields with an animation

## Demo

[Check it live!](http://juicy.github.io/juicy-input) (Soon!)

## Usage

1. Install the component using [Bower](http://bower.io/):

    ```sh
    $ bower install juicy-input --save
	```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/juicy-input/src/juicy-input.html">
    ```

3. Start using it!

    ```html
	 <h4>Examples</h4>
     <juicy-input type="text" value="Hello you" label="The label" title="The title" editable></juicy-input>
	 <juicy-input type="number" value="123" label="The label again" title="The Title again" editable></juicy-input>
	 <juicy-input type="date" value="" mode="input" label="yet another label" editable></juicy-input>
    ```

## Attributes

Attribute         | Type           					| Default      | Description
---               | ---            					| ---          | ---
`type`            | *String*, *number*, *date*      | `none`       |  
`value`   	      | *String*, *number*, *date*		| `none`       | Value imported, you can use javascript or similar
`label`     	  | *String*     				    | ``    	   | Label of field
`title`    		  | *String*     				    | ``           | Title of field
`mode`            | *Color*       				    | ``      	   | For date field, must set editable or readonly
`editable`   	  |             					| ``           | If exists, then field is editable


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

MIT
