# Polyweight
### A color theme without much color

Currently, Polyweight is available for only `highlight.js`, but VS Code and Atom themes will be comming in the future.


### Highlight.js
Download `polyweight-hljs.css`, and add it to the HTML pages you want to use syntax highlightin in. Follow the instructions for [highlight.js](highlightjs.org) to add it aswell.

By default, Polyweight will use the dark theme, just add the class `light` to your code block as shown:
```html
<pre class="light"><code>
// Code
</code></pre>
```

### A note on fonts
Polyweight uses a **lot** of font weights. Currently, the following are in use: `400,400i,500,500i,600,600i,700,700i`. If you wish to use a font other than `IBM Plex Mono`, please make sure it has all of the above weights available otherwise things won't look good.