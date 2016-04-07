# hsv-for-stylus

stylus hsv function

usage:

```
   color: hsv(hsvhue(#313233), hsvsaturation(#313233), hsvvalue(#313233));
   color: hsv(hsvhue(#313233), hsvsaturation(#313233) + 4%, hsvvalue(#313233));
```
result:

```
    color: #313233;
    color: #2f3133;
```

onLine compiler: http://beautifytools.com/stylus-compiler.php

reference:

* http://axonflux.com/handy-rgb-to-hsl-and-rgb-to-hsv-color-model-c
* http://www.sitepoint.com/hsb-colors-with-sass/
