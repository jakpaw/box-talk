### 2 solutions for 2 use cases

- replace as with tagName, which only supports div and span <!-- .element: class="fragment" -->
<br />
<img src="code/tag-name.svg" /> <!-- .element: class="fragment" -->
  <!-- <pre><code data-trim class="language-tsx">
&lt;Box tagName="span" padding="small"&gt;...&lt;/Box&gt;
</code></pre> -->
- add a styling util function which returns classNames <!-- .element: class="fragment" -->
<br />
<img src="code/styling-util.svg" /> <!-- .element: class="fragment" -->
<!-- <pre><code data-trim class="language-tsx">
&lt;Card className={styles({padding: 'small'})}&gt;...&lt;/Card&gt;
</code></pre> -->
