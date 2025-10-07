### Polymorphic React components

<!-- <pre><code data-line-numbers="1-2|4-6" data-trim>
&lt;Button as="a" href="https://www.google.com"&gt;Google&lt;/Button&gt;
&lt;Button as="button" onClick={...}&gt;Click me&lt;/Button&gt;

const Button = ({ as: Component, ...props }) =&gt; {
  return &lt;Component {...props} className={...} /&gt;
};
</code></pre> -->

- Users can pass the element to render as a prop

<img src="code/poly.svg" />
