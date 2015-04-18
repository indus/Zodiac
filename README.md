[![JS.ORG](https://img.shields.io/badge/js.org-zodiac-ffb400.svg?style=flat-square)](http://js.org)

particle background inspired by [jnicol/particleground](https://github.com/jnicol/particleground)

**Demo** [zodiac.js.org](http://zodiac.js.org/)

``` js
new Zodiac('zodiac',                      // HTMLCanvasElement or id
   {                                      //// OPTIONS
      directionX: 0,                      // -1:left;0:random;1:right
      directionY: -1,                     // -1:up;0:random;1:down
      velocityX: [.1, .2],                // [minX,maxX]
      velocityY: [.5, 1],                 // [minY,maxY]
      bounceX: true,                      // bounce at left and right edge
      bounceY: false,                     // bounce at top and bottom edge
      parallax: .5,                       // float [0-1...]; 0: no paralax
      pivot: 0,                           // float [0-1...]; pivot level for parallax;
      density: 10000,                     // px^2 per node
      dotRadius: [2, 5],                  // px value or [minR,maxR]
      backgroundColor: 'rgb(9,9,9)',      // default transparent; use alpha value for motion blur and ghosting
      dotColor: 'rgba(99,99,99,.3)',
      linkColor: 'rgb(99,99,99)',
      linkDistance: 50,
      linkWidth: 2
   });
```
