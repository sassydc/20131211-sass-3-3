### Sass 3.3

.scss

<pre><code>.block {
  ...

  @at-root {
    .#{&}-element { ... }
  }
}</code></pre>

.css

<pre><code>.block { ... }
.block-element { ... }</code></pre>

<br />

Even Better: [BEM Mixin Example](http://sassmeister.com/gist/6994632) by [Scott Kellum](https://twitter.com/scottkellum)
