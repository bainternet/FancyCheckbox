FancyCheckbox
=============
FancyCheckbox is a simple and lightweight (less then 1k min and gziped) jQuery plugin to create iPhone styled checkboxes based on [this tutorial](http://www.webstuffshare.com/2010/03/stylize-your-own-checkboxes/) and created By the need of a GPL licensed 

![FancyCheckbox](http://i.imgur.com/2Xy6d.png)



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

###Events:
<table>
  <tr>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <th>beforeLoad</th>
    <td>Triggered just before the fancy checkbox is loaded to the DOM</td>
  </tr>
  <tr>
    <th>afterLoad</th>
    <td>Triggered just after the fancy checkbox is loaded to the DOM</td>
  </tr>
  <tr>
    <th>beforeChangeIphone</th>
    <td>Triggered just before the fancy checkbox (iPhone styled) is changed</td>
  </tr>
  <tr>
    <th>afterChangeIphone</th>
    <td>Triggered just after the fancy checkbox (iPhone styled) is changed</td>
  </tr>
  <tr>
    <th>beforeChangeFirerift</th>
    <td>Triggered just before the fancy checkbox (Firerift styled) is changed</td>
  </tr>
  <tr>
    <th>afterChangeFirerift</th>
    <td>Triggered just after the fancy checkbox (Firerift styled) is changed</td>
  </tr>
  
</table>

##Author
Ohad Raz http://en.bainternet.info
##License:

Copyright © 2012 Ohad Raz, <admin@bainternet.info>  ,Dual licensed under the [MIT](http://www.opensource.org/licenses/mit-license.php) and [GPL](http://www.gnu.org/licenses/gpl.html) licenses.




