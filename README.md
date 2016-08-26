# ember-d3

`ember-d3` is a shim that allows easy integration of d3 visualizations into Ember apps. It is not intended as a widget library: visualizations are still drawn natively with d3, but this library provides handling of functionality that is common to all d3 visualizations:
- delegation of data binding from Ember to d3 (?)
- optional automatic sizing of visualizations to their parent element


## Installation

TODO: Describe the installation process

## Usage

```
{{viz
  data = vizData
  draw = drawFn
  update = updateFn
  autoSize = true
}}
```

- `data` is the visualization's data, which
- `draw` is the fn that draws the visualization on component initialization and, if `autoSize = true`, when the component's parent element's dimensions change
- `update` is the fn that updates the visualization on changes to `data`, or used during animations

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

TODO: Write history

## Credits

TODO: Write credits

## License

TODO: Write license
