# colormap.js
Simple color mapping tool without any external dependencies.

## how to use
```
var colors = colormap({
  numberOfShades: 6, // default is 72
  map: 'cool' // default is 'jet'
});
```

returns:  
```
["#00ffff", "#33ccff", "#6699ff", "#9966ff", "#cc33ff", "#ff00ff"]
```

## available maps
jet  
hsv  
hot  
cool  
spring  
summer  
autumn  
winter  
bone  
copper  
greys  
yignbu  
greens  
yiorrd  
bluered  
rdbu  
picnic  
rainbow  
portland  
blackbody  
earth  
electric  
