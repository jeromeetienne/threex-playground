threexplayground
================

It is a 
[htmleditor](https://github.com/mrdoob/htmleditor)
from 
[mrdoob](http://mrdoob.com).
with all 
[threex](http://jeromeetienne.github.io/threex/)
[bower](http://bower.io/)
packages. It is a simple way to play around with 
[three.js](http://threejs.org)
and
[threex](http://jeromeetienne.github.io/threex/)

## Notes on updating bower.json

Get the list of threex published on bower with this.

```bash
bower search threex.
```

Check they are all in the bower.json ```dependencies``` field. It should look like that.

```json
  "dependencies": {
    "threex.windowresize": "*"
  }
```