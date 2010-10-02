# KEYS.css

A simple stylesheet to render beautiful keyboard-styled elements.

## Usage

Download the stylesheet and include it via

    <link rel="stylesheet" href="keys.css" type="text/css" />
    
The stylesheet comes with two classes for light and dark keys for good visibility on every background. Since most websites have light backgrounds, the light style is the default.

    // Dark keys:
    <em class="key">ctrl</em> + <em class="key">S</em>
    // ...or...
    <em class="key dark">ctrl</em> + <em class="key dark">S</em>
    // ...or...
    <span class="dark-keys">
        <em class="key">ctrl</em> + <em class="key">S</em>
    </span>
    
    // Light keys:
    <em class="key light">ctrl</em> + <em class="key light">S</em>
    // ...or...
    <span class="light-keys">
        <em class="key">ctrl</em> + <em class="key">S</em>
    </span>
    
That's all. The size of the keys depends on the set `font-size`.

## License

MIT License (see LICENSE.txt)