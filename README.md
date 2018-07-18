# flxMenu
The flxMenu plugin is a responsive, cross-browser jQuery plugin that helps you create dropdown navigation for both desktop and mobile devices.

## Features 
- automatically switches to a mobile-friendly toggle menu when the window width reaches a specified breakpoint.
- supports infinite levels of sub menus.
- supports multi-column dropdown navigation.
- popup menu slides in from top, left or right hand side.
- accordion-style menu where all the menu items will be collapsed into a dropdown toggle menu on small screens.
- supports keyboard navigation in desktop mode.
 
## Usage 
Include the JS and CSS 
```HTML
<script src="jquery.flxMenu.min.js"></script>
<link href="flxMenu.css" rel="stylesheet" type="text/css">	
```
Initialize
``` javascript
$(function(){
  $('#MenuToMove').flxMenu($('#navTrigger'), options);
});
```
## Examples
[flxMenu info page](http://jquery.LTS-Tools.com/flxMenu.php "LTS-Tools jQuery Page")
