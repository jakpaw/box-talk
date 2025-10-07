### asChild pattern 👶

<!-- <pre><code data-trim class="language-xml">
&lt;Box asChild onClick={...} border="subtle"&gt;
  &lt;Card gap="small"&gt;...&lt;/Card&gt;
&lt;/Box&gt;
</code></pre> -->

<img src="code/as-child.svg" />

- Type safety problems <!-- .element: class="fragment" -->
  - No way to check if Card supports onClick ❌ <!-- .element: class="fragment" -->
- Where to put the props? On parent? On child? <!-- .element: class="fragment" -->
  <img src="code/duplicate.svg" />
  <!-- <pre><code data-trim class="language-xml">
  &lt;Box asChild onClick={...}&gt;
      &lt;Card gap="small" onClick={...}&gt;...&lt;/Card&gt;
  &lt;/Box&gt;
  </code></pre> -->
