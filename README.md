FancyCheckbox
=============
![FancyCheckbox](http://i.imgur.com/2Xy6d.png)

FancyCheckbox is a simple and lightweight jQuery plugin to create Iphone styled checkboxes based on [this tutorial](http://www.webstuffshare.com/2010/03/stylize-your-own-checkboxes/)

##Usage:
Include nessesary JS and CSS files
```html
<link rel="stylesheet" type="text/css" media="screen, projection" href="FancyCheckbox.css" />
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
<script src="FancyCheckbox.js"></script>
```
Then simple call the plugin on any element you want (assuming that is a checkbox)
```html
<script>
  jQuery(document).ready(function($) {
    //all checkboxes
    $(":checkbox").FancyCheckbox();
  });
</script>
```

###Options:
<table>
  <tr>
    <th>Option</th>
    <th>Defualt</th>
    <th>Description</th>
  </tr>
  <tr>
    <th>style</th>
    <td>iphone</td>
    <td>(string) accepts iphone,firerift, what type of fancycheckbox to create</td>
  </tr>
  <tr>
    <th>offClass</th>
    <td>no-fancy</td>
    <td>(string) class to disable, elements with this class will not be fancy</td>
  </tr>
</table>

##Author
Ohad Raz http://en.bainternet.info
##License:

Copyright 2012, Ohad Raz

Dual licensed under the MIT and GPL licenses:

http://www.opensource.org/licenses/mit-license.php

http://www.gnu.org/licenses/gpl.html
