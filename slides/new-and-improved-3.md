### 3.3

.scss

<pre><code>.block-element {
  ...

  @at-root {
    #{&}--modifier { ... }
  }
}</code></pre>

.css

<pre><code>.block-element { ... }
.block-element--modifier { ... }</code></pre>
