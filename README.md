## three-subdivision-modifier

This is the Three.js subdivision modifier "extras" package found in the [Three.js source](https://github.com/mrdoob/three.js/blob/master/examples/js/modifiers/SubdivisionModifier.js) ([example](http://threejs.org/examples/#webgl_modifier_subdivision)).

It's loosely based on the [three-orbit-controls](https://github.com/mattdesl/three-orbit-controls) package.

## Usage:

```js
var SubdivisionModifier = require('three-subdivision-modifier');

var modifier = new SubdivisionModifier( 2 ); // Number of subdivisions

modifier.modify( geometry ); // Modifies geometry in place
```

See [the offical Three.js example](http://threejs.org/examples/#webgl_modifier_subdivision) for more information and usage.
