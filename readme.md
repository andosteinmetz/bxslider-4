#bxSlider NX
[http://bxslider.com](http://bxslider.com)

Written by: Steven Wanderski - [http://stevenwanderski.com](http://stevenwanderski.com)

##License
Released under the MIT license - http://opensource.org/licenses/MIT

##Changes
* Code cleanup
* Replaced deprecated jQuery methods with
* Removed broken lazy loading functionality
* Added onSliderReady callback. The event is triggered before initializing touch handler is initialized. Use this in order to implement lazy loading of the content (e.g. images)
* Introduced sliderPadding property: Setting it will hint the previous/next slide by the amount of pixels defined (default: 0)
* Added Windows Phone 8 touch handling (not tested yet)