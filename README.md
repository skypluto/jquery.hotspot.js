# jquery.hotspot.js
jQuery Hotspot Plugin

Using the plugin is simple.

## Installation
* Clone and include the plugin

## Usage
* Default selector
```javascript
mainselector: '#hotspotImg',
selector: '.hot-spot',
imageselector: '.img-responsive',
tooltipselector: '.tooltip',
bindselector: 'hover'
```

* Sample HTML
** Defining the x and y position
```html
<div id="hotspotImg" class="responsive-hotspot-wrap row">
  <img class="img-responsive" src="img/banners/main.png">
	<div class="hot-spot" x="800" y="223">
		<div class="tooltip">
			<div class="col-sm-6">
				<img src="img/index/col1.png">
			</div>
			<div class="col-sm-6">
				<h4>Lorem Ipsum Title 1</h4>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
			</div>
		</div>
	</div>
	<div class="hot-spot" x="1534" y="487">
		<div class="tooltip">
			<div class="col-sm-6">
				<img src="img/index/col2.png">
			</div>
			<div class="col-sm-6">
				<h4>Lorem Ipsum Title 2</h4>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
			</div>		
		</div>		
	</div>
	<div class="hot-spot" x="361" y="408">
		<div class="tooltip">
			<div class="col-sm-6">
				<img src="img/index/col3.png">
			</div>
			<div class="col-sm-6">
				<h4>Lorem Ipsum Title 3</h4>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
			</div>
		</div>		
	</div>	
</div>
```

* Triggering the hotspot
```javascript
$('#hotspotImg').hotSpot(); // Use hover event on the hotspot
```

* Triggering the hotspot by overriding the hover event
```javascript
$('#hotspotImg').hotSpot({bindselector: 'click'}); // Use click event on the hotspot
```

