### The Box component

<!-- <pre><code data-line-numbers="1-2|4-8" data-trim class="language-xml">
&lt;Box as="button" onClick={...} padding="large"&gt;...&lt;/Box&gt;
&lt;Box as="Card" border="subtle"&gt;...&lt;/Box&gt;

const Box = ({ as: Component, ...props }) =&gt; {
  const { styleProps, otherProps } = extractStyleProps(props);
  const classNames = getClassNames(styleProps);
  return &lt;Component {...otherProps} className={classNames} /&gt;
};
</code></pre> -->

<img src="code/box.svg" />
