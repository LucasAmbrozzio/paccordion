# Paccordion
A dead simple accordion plugin


## Requirements
[paccordion](https://github.com/morshedx/paccordion) requires the latest version of [jQuery](http://jquery.com)


## Usages

Include scripts and style inside `<head>` tag of your document

```
<link rel="stylesheet" href="path-to-style/style.css">

<script src="path-to-script/jquery-1.11.3.min.js"></script>
<script src="path-to-script/paccordion.js"></script>
```
## Markup
```
<div class="accordion-wrapper">
	<div class="ac-pane active">
		<a href="#" class="ac-title">
			<!-- accordion title here -->
		</a>
		<div class="ac-content">
			<!-- accordion content here  -->
		</div>
	</div>
</div>
```

### For accordion 
Just add a data attribute to title for accordion 

```
<a href="#" class="ac-title" data-accordion="true">
```
