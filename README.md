jPushMenu
=========

A jQuery version of Slide and Push Menus

I added a param called fixedElements because I had a case with a mobile fixed header not working properly on chrome/android. You specify the fixed elements in the options:

```
$('.toggle-menu').jPushMenu({fixedElements: '#fixed'});
```

If you want a smooth animation, add the .cbp-spmenu-push class to the fixed element.

Currently works only for elements with postion left: 0
