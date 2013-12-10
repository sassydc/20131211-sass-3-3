.scss

<pre><code>.block-element {

  & > a { ... }

  .unauthenticated & { ... }
}</code></pre>

.css

<pre><code>.block-element > a { ... }
.unauthenticated .block-element { ... }</code></pre>
