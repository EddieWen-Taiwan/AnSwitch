## AnSwitch
This is a simple web component - switch.  
I implement Andrew's [Yet another toggle animation](https://dribbble.com/shots/2309834-Yet-another-toggle-animation)

__Implementataion DEMO__  
<http://github.eddiewen.me/Implementation/Buttons/Andrew/>

----

#### Usage
~~~html
<!-- HTML -->
<div id="answitch">
	<div class="circle">
		<div class="an-line an-left"></div>
		<div class="an-line an-right"></div>
	</div>
</div>
~~~
And you need to include `AnSwitch.css` file. I set the width and height to 2/1(200px/100px). You could set .answitch's width and height with any value, but just keep the radio.

~~~javascript
// with jQuery
$('.circle').on( 'click', function(){
	$('#answitch').toggleClass('checked');
});
~~~
Use your way to add/remove classname - `checked` on `.answitch`.

----
Here is Pavel Mazurin's [PMZSwitch](https://github.com/kovpas/PMZSwitch) in Swift