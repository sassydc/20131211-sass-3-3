### Sass 3.3

.scss

<pre><code>$color: red;

.foo {
  $color: blue !global;
  color: $color;
}

.bar {
  color: $color;
}</code></pre>

.css

<pre><code>.foo {
  color: blue;
}

.bar {
  color: blue;
}</code></pre>
