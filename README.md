## AnSwitch
This is a simple web component - switch.  
I implement Andrew's [Yet another toggle animation](https://dribbble.com/shots/2309834-Yet-another-toggle-animation)
![switch](switch.gif)

__Implementataion DEMO__  
<http://github.eddiewen.me/DailyWeb/Button/Andrew/>

----

#### Usage
~~~html
<!-- HTML -->
<div id="answitch">
	<div class="circle"></div>
</div>
~~~
And you need to include `AnSwitch.min.css` file. I set the width and height to 2/1(200px/100px). You could set `#answitch`'s width and height with any value, but keep the radio.

~~~javascript
// with jQuery
$('.circle').on( 'click', function() {
	$('#answitch').toggleClass('checked');
});
~~~
Use your way to add/remove class - `checked` on `#answitch`.

If you want a larger switch area, just change the `box-shadow` value.

~~~css
#answitch {
	box-shadow: 0px 0px 0px 0.3rem white;
}
~~~

----
Here is Pavel Mazurin's [PMZSwitch](https://github.com/kovpas/PMZSwitch) in Swift
