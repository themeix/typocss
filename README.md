# Fix your content typography with typography-fix

This will faster the process to make a theme with proper typography for any HTML tempaltes, Ghost Themes, Jekyll Themes, WordPress Theme etc.

## How it works

Typography-fix will work if you add the class 'typofix' in your content markup. 
Example :

```
<div class="entry-content my-1 typofix">
	<p>Here is my content need to fix</p>
	<blockquote>
	   <p>Stay hungry. Stay foolish.</p>
	</blockquote>	
</div>
```

To change the design you can customize the css variables used in typography-fix.

Example

```
.typofix { 
  --background-color: #F3F6FA; 
  --border-color: #DBE2F2;
  --color: #404459;
  --blockquote-color: rgba(0,0,0,.2);
  --mark-color: rgba(0, 140, 255, 0.1);
  line-height: 1.0;
  text-rendering: optimizeLegibility;
}
```
