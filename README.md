# Saving For Retirement

### Mobile app to calculate the monthly savings required to provide enough money for retirement

    * HTML5, CSS3, javascript
    * jQuery
    * Twitter Bootstrap
    * jQuery Template
    * several javascript financial functions of my own

FWIW having built this app in both jQuery Mobile and Twitter Bootstrap, I prefer Bootstrap: its formatting seems simpler and the out-of-the box defaults suit me better.

jQuery Mobile has built-in support for multi-page apps in one file, but   
```
$('...').show(); 
$('...').hide();
```   
 does the trick independent of framework (or none at all).
 
 
The operation of this web app is entirely driven by the JavaScript functions contained within ```index.html```; 
the formatting depends on external calls so an app cache is provided to insulate the user from breaks in connectivity.
