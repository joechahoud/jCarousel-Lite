jCarousel-Lite
==============

This is a modified version of the jquery plugin jCarousel Lite found on http://gmarwaha.com/jquery/jcarousellite/
It allows you to define which direction the scroll is going to be in both cases: vertical scroll and horizontal scroll.
The original version presets the scroll direction in case of 
  - horizontal scroller: scroll left-to-right
  - vertical scroller: scroll top-to-bottom
This modified version adds the possibility to set the scroll direction to:
  - horizontal scroller: direction = 1 to scroll left-to-right or direction = 0 to scroll right-to-left
  - vertical scroller: direction = 1 to scroll top-to-bottom or direction = 0 to scroll bottom-to-top

To set the direction of the scroller to scroll from right to left, all you have to do is add 
"direction" attribute like so:

  $(".default .jCarouselLite").jCarouselLite({  
      btnNext: ".default .next",
      btnPrev: ".default .prev",
      direction: 0
  });

Enjoy :)
