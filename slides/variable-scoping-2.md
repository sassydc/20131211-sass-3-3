### Sass 3.2

.scss

<pre><code>$color: red;

.foo {
  $color: blue;
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
  color: red;
}</code></pre>
