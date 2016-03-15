# Sublime 3 snippets own collection

Various snippets for Sublime Text 3.

## Bootstrap

[`carousel`](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/bootstrap/carousel.sublime-snippet)

```
	<div id="carousel-id" class="carousel slide" data-ride="carousel">
		<ol class="carousel-indicators">
			<li data-target="#carousel-id" data-slide-to="0" class=""></li>
			<li data-target="#carousel-id" data-slide-to="1" class=""></li>
			<li data-target="#carousel-id" data-slide-to="2" class="active"></li>
		</ol>
		<div class="carousel-inner" role="listbox">
			<div class="item">
				<img alt="" src="https://www.fillmurray.com/900/500">
				<div class="container">
					<div class="carousel-caption">
						<p>test</p>
					</div>
				</div>
			</div>
			<div class="item">
				<img alt="" src="https://www.fillmurray.com/900/500">
				<div class="container">
					<div class="carousel-caption">
						<p>test</p>
					</div>
				</div>
			</div>
			<div class="item active">
				<img alt="" src="https://www.fillmurray.com/900/500">
				<div class="container">
					<div class="carousel-caption">
						<p>test</p>
					</div>
				</div>
			</div>
		</div>
		<a class="left carousel-control" href="#carousel-id" data-slide="prev">
			<span class="icon icon-arrow-left" aria-hidden="true"></span>
			<span class="sr-only">Previous</span>
		</a>
		<a class="right carousel-control" href="#carousel-id" data-slide="next">
			<span class="icon icon-arrow-right" aria-hidden="true"></span>
			<span class="sr-only">Next</span>
		</a>
	</div>
```

[`forminput`](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/bootstrap/forminput.sublime-snippet)

```
	<div class="form-group">
		<label for="">label</label>
		<input type="text" class="form-control" name="" id="" placeholder="placeholder">
	</div>
```

[`formselect`](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/bootstrap/formselect.sublime-snippet)

```
	<div class="form-group">
		<label for="">label</label>
		<select name="" id="inputLabel" class="form-control">
			<option value=""></option>
		</select>
	</div>
```

[`formtextarea`](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/bootstrap/formtextarea.sublime-snippet)

```
	<div class="form-group">
		<label for="">label</label>
		<textarea name="" id="input" class="form-control" rows="3">label</textarea>
	</div>
```

[`modal`](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/bootstrap/modal.sublime-snippet)

```
	<a class="btn btn-primary" data-toggle="modal" href='#modal-id'>Trigger modal</a>
	<div class="modal fade" id="modal-id">
		<div class="modal-dialog">
			<div class="modal-content">
				<div class="modal-header">
					<button type="button" class="close" data-dismiss="modal" aria-hidden="true">&times;</button>
					<h4 class="modal-title">Modal title</h4>
				</div>
				<div class="modal-body">
				</div>
				<div class="modal-footer">
					<button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
					<button type="button" class="btn btn-primary">Save changes</button>
				</div>
			</div>
		</div>
	</div>
```

[`navbar`](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/bootstrap/navbar.sublime-snippet)

```
	<nav class="navbar navbar-default" role="navigation">
		<div class="container">
			<div class="navbar-header">
				<button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar">
					<span class="sr-only">Toggle navigation</span>
					<span class="icon icon-menu"></span>
				</button>
				<a class="navbar-brand" href="#">Title</a>
			</div>
			<div class="collapse navbar-collapse">
				<ul class="nav navbar-nav navbar-right">
					<li><a href="#">Link</a></li>
					<li class="dropdown">
						<a href="#" class="dropdown-toggle" data-toggle="dropdown">Dropdown <b class="caret"></b></a>
						<ul class="dropdown-menu">
							<li><a href="#">Action</a></li>
							<li><a href="#">Another action</a></li>
							<li><a href="#">Something else here</a></li>
							<li><a href="#">Separated link</a></li>
						</ul>
					</li>
				</ul>
			</div>
		</div>
	</nav>
```

[makecolmixin](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/bootstrap/makecolmixin-snippet)

```
@mixin make-eight-column($gutter: $grid-gutter-width, $breakpoint: $screen-sm-min) {
  position: relative;
  min-height: 1px;
  padding-left:  ( / 2);
  padding-right: ( / 2);

  @media (min-width: $breakpoint) {
    float: left;
    width: percentage((1 / 8));
  }
}
```

## HTML

[skipnav](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/html/skipnav.sublime-snippet)

```
	<div class="skip-nav">
		<ul>
			<li><a href="#navigation">Aller au menu</a></li>
			<li><a href="#content" accesskey="s">Aller au contenu</a></li>
			<li><a href="#search" accesskey="4">Aller à la recherche</a></li>
		</ul>
	</div>
```

[tablefull](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/html/tablefull.sublime-snippet)

```
	<table>
		<thead>
			<tr>
				<th></th>
				<th></th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td></td>
				<td></td>
			</tr>
		</tbody>
	</table>
```

## JavaScript

[ifun](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/javaScript/ifun.sublime-snippet)

```
	;(function() {
		'use strict';

	}());
```

[ifor](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/javaScript/ifor.sublime-snippet)

```
	for (var i = 0, len = arr.length; i < len; i++) {
		arr[i]
	}
```

[module](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/javaScript/module.sublime-snippet)

```
	var moduleName = (function() {
		'use strict';
		var moduleName = {
			init: {
			}
		};
		return moduleName;
	}());
```

[dynamictextarea](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/javaScript/dynamictextarea.sublime-snippet)

```
	function elasticArea() {
		$('.js-elasticArea').each(function(index, element) {
			var $elasticElement = $(element),
				delta = parseInt($elasticElement.css('paddingBottom'), 10) + parseInt($elasticElement.css('paddingTop'), 10) || 0,
				elasticElement = element,
				initialHeight = initialHeight || $elasticElement.height();
	
			function resize() {
				$elasticElement.height(initialHeight);
				$elasticElement.height(elasticElement.scrollHeight - delta);
			}
	
			$elasticElement.on('input change keyup', resize);
			resize();
		});
	
	}
	elasticArea();
```

[dynamicheader](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/javaScript/dynamicheader.sublime-snippet)

```
function hasScrolled() {
		var scrollTop = $(window).scrollTop();
		if (Math.abs(lastScrollTop - scrollTop) <= scrollDelta)
			return;
		if (scrollTop > lastScrollTop && scrollTop > headerHeight) {
			$header.addClass('header-scroll-down');
		}
		else if (scrollTop + $(window).height() < $(document).height()) {
			$header.removeClass('header-scroll-down');
		}
		lastScrollTop = scrollTop;
	}

	$(window).on('scroll', function() {
		didScroll = true;
	});

	setInterval(function() {
		if (didScroll) {
			hasScrolled();
			didScroll = false;
		}
	}, 250);
```

[smoothscroll](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/javaScript/smotthscroll.sublime-snippet)

```
// Smooth Scroll
	$('a[href*=#]:not([href=#])').click(function() {
		if (location.pathname.replace(/^\//,'') == this.pathname.replace(/^\//,'') && location.hostname == this.hostname) {
			var target = $(this.hash);
			target = target.length ? target : $('[name=' + this.hash.slice(1) +']');
			if (target.length) {
				$('html,body').animate({
					scrollTop: target.offset().top-65
				}, 1000);
				return false;
			}
		}
	});
```

## React

[reacthtml](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/react/reacthtml.sublime-snippet)

```
<!DOCTYPE html>

	<html lang="en">
	<head>
		<meta charset="UTF-8">
		<title>Hello React!</title>
		<script src="https://cdnjs.cloudflare.com/ajax/libs/react/0.14.7/react.min.js"></script>
		<script src="https://cdnjs.cloudflare.com/ajax/libs/react/0.14.7/react-dom.min.js"></script>
		<script src="https://cdnjs.cloudflare.com/ajax/libs/babel-core/5.8.23/browser.min.js"></script>
	</head>
	<body>
		<div id="example"></div>
		<script type="text/babel">
			ReactDOM.render(
				<h1>Hello, world!</h1>,
				document.getElementById('example')
			);
		</script>
	</body>
	</html>
```

[reactclass](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/react/reactclass.sublime-snippet)

```
var HelloWorld = React.createClass({
		render: function(){
			return (
				<h1>Hello, world!</h1>
			);
		}
	});

	React.render(<HelloWorld />, document.getElementById('example'));
```

## Web Components

[polymerhtml](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/webComponents/polymerhtml.sublime-snippet)

```
<!doctype html>
	<html>
	<head>
		<meta charset="utf-8">
		<title>paper-button demo</title>
		<script src="https://cdn.rawgit.com/download/polymer-cdn/1.2.3.2/lib/webcomponentsjs/webcomponents-lite.js
		"></script>
		<script>
			window.Polymer = window.Polymer || {};
			window.Polymer.dom = 'shadow';
		</script>
		<!-- import a component that relies on Polymer -->
		<link rel="import" href="https://cdn.rawgit.com/download/polymer-cdn/1.2.3.2/lib/paper-button/paper-button.html">
	</head>
	<body>
		<paper-button>link</paper-button>
		<paper-button raised>raised</paper-button>
		<paper-button toggles raised>toggles</paper-button>
		<paper-button disabled>disabled</paper-button>
	</body>
	</html>
```

[polymerelement](https://github.com/tibomahe/sublime3-snippets-own-collection/blob/master/webComponents/polymerelement.sublime-snippet)

```
<dom-module id="element-name">
		
		<template>
			<style>
				/* CSS rules for your element */
			</style>

			<!-- local DOM for your element -->

			<div>{{greeting}}</div> <!-- data bindings in local DOM -->
		</template>
		
		<script>
			// element registration
			Polymer({
				is: "element-name",

				// add properties and methods on the element's prototype

				properties: {
				// declare properties for the element's public API
				greeting: {
					type: String,
					value: "Hello!"
				}
			}
		});
		</script>
		
	</dom-module>
```



