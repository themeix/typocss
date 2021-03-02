# Fix your content typography with typography-fix

This will faster the process to make a theme with proper typography for any HTML templates, Ghost Themes, Jekyll Themes, WordPress Theme etc.

## How it works

Typography-fix will work if you add the class 'typofix' in your content markup. But make sure you added the typofix.css in your project.
Example :

```
<div class="entry-content typofix">
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
	--border-color: #e3e4e4;
	--color: #666;
	--blockquote-color: #36f;
	--mark-color: #ffeb3b;
	--body-line-height: 1.7;
	--heading-line-height: 1.3;
	--base-font-size: 16px;
	text-rendering: auto;
}
```
