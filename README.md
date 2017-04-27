# \<polymer-dragula\>

Polymer implementation of dragula D&amp;D handling

Example:
```html
<style is="custom-style" include="polymer-dragula-styles">
    .column {
        border: 1px dotted #0d47a1;
        margin: 5px;
        display: block;
        padding: 15px;
        background-color: #ffcc80;
        cursor: move;
        cursor: grab;
        cursor: -moz-grab;
        cursor: -webkit-grab;
    }
</style>

<polymer-dragula>
    <div>
        <div class="column">
            <p>Item 1</p>
        </div>
        <div class="column">
            <p>Item 2</p>
        </div>
        <div class="column">
            <p>Item 3</p>
        </div>
        <div class="column">
            <p>Item 4</p>
        </div>
        <div class="column">
            <p>Item 5</p>
        </div>
    </div>
</polymer-dragula>
```
note: remember to import `polymer-dragula/polymer-dragula.html`

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
