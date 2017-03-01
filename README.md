[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)]()

## &lt;paper-compare&gt;

paper-compare is a way to compare two lists and move items from one list to another.

### Usage
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-compare.html">
    <link rel="import" href="../paper-material/paper-material.html">
    <link rel="import" href="../paper-item/paper-item.html">
    <link rel="import" href="../iron-demo-helpers/demo-pages-shared-styles.html">
    <style is="custom-style" include="demo-pages-shared-styles">
    	
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-compare left-title="LeftList" right-title="RightList">
	<div role="listbox" class="compare-list" id="left">
		<paper-item>Kevin M</paper-item>
		<paper-item>John G</paper-item>
	</div>
	<div role="listbox" class="compare-list" id="right">
		<paper-item>Alicia H</paper-item>
		<paper-item>Samantha K</paper-item>
		<paper-item>Melissa M</paper-item>
	</div>
</paper-compare>
```
