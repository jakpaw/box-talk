### Box component issues

- Props conflicts <!-- .element: class="fragment" -->
  - Is gap a prop of Box or Card? 🤷 <!-- .element: class="fragment" -->
      <!-- <pre><code data-trim class="language-xml">
      &lt;Box as="Card" gap="small"&gt;...&lt;/Box&gt;
      </code></pre> -->
    <img src="code/box-gap.svg" />
- ForwardRef <!-- .element: class="fragment" -->
  - Complicated generic TS types (~100 lines 😱) <!-- .element: class="fragment" -->
