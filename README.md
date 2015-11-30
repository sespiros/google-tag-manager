# &lt;google-tag-manager&gt;

Polymer 1.2 wrapper element for google tag manager.

So far only basic functionality is implemented, I've not messed up with extra dataLayer support and stuff.

Check out the [demo](http://sespiros.github.io/google-tag-manager/)

## Setup
Install with bower or [download the zip](https://github.com/sespiros/google-tag-manager/archive/v0.0.1.zip)
```bash
bower install --save sespiros/google-tag-manager
```
Import it in your code
```html
<!-- for relative paths -->
<link rel="import"href="../bower_components/google-tag-manager/google-tag-manager.html">
```

## Usage
```html
<google-tag-manager cid="GTM-XXXXXX"></google-tag-manager>
```

## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview your element at
`http://localhost:8080/components/google-tag-manager/`.

## Contribute
Feel free to extend it or propose new functionality
