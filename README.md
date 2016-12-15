# \<polymer-dragula\>

Polymer implementation of dragula D&amp;D handling


Example:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="polymer-dragula.html">
  <style>

        .vertical-section-container {
            max-width: 600px;
        }

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

        .gu-mirror {
            position: fixed !important;
            margin: 0 !important;
            z-index: 9999 !important;
            opacity: 0.8;
            -ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=80)";
            filter: alpha(opacity=80);
            cursor: grabbing;
            cursor: -moz-grabbing;
            cursor: -webkit-grabbing;
        }

        .gu-hide {
            display: none !important;
        }

        .gu-unselectable {
            -webkit-user-select: none !important;
            -moz-user-select: none !important;
            -ms-user-select: none !important;
            user-select: none !important;
        }

        .gu-transit {
            opacity: 0.2;
            -ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=20)";
            filter: alpha(opacity=20);
        }

    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
    <polymer-dragula>
        <div class="row-holder">
            <div class="column">
                <p>item-1</p>
            </div>
            <div class="column">
                <p>item-2</p>
            </div>
            <div class="column">
                <p>item-3</p>
            </div>
            <div class="column">
                <p>item-4</p>
            </div>
            <div class="column">
                <p>item-5</p>
            </div>
        </div>
    </polymer-dragula>
```

</template>

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
