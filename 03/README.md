## 03 update to es2015, update code style

convert to [ES2015](https://babeljs.io/docs/learn-es2015/) with [lebab](https://github.com/lebab/lebab)

```shell
➜  03 git:(master) ✗ lebab es5.js -o es6.js --transform arrow
➜  03 git:(master) ✗ lebab es6.js -o es6.js --transform for-of
➜  03 git:(master) ✗ lebab es6.js -o es6.js --transform arg-spread
➜  03 git:(master) ✗ lebab es6.js -o es6.js --transform obj-method
➜  03 git:(master) ✗ lebab es6.js -o es6.js --transform obj-shorthand
➜  03 git:(master) ✗ lebab es6.js -o es6.js --transform multi-var
➜  03 git:(master) ✗ lebab es6.js -o es6.js --transform let
➜  03 git:(master) ✗ lebab es6.js -o es6.js --transform template
```

do check out the other examples in this `world map` series:  

[world map 00 original example](https://bl.ocks.org/jeremycflin/b43ab253f3ae02dced07)  
[world map 01 fix tooltip value](https://bl.ocks.org/micahstubbs/01529b106c93f9b649c4006de5c79b80)  
[world map 02 d3 v4](https://bl.ocks.org/micahstubbs/8e15870eb432a21f0bc4d3d527b2d14f)  
**world map 03 es2015 + update code style**  
[world map 04 manual breaks + threshold scale](https://bl.ocks.org/micahstubbs/535e57a3a2954a129c13701fe61c681d)  
[world map 05 linear breaks + quantize scale](https://bl.ocks.org/micahstubbs/c14d8bda8e337da6c836a526ad1a7c5a)  
[world map 06 linear breaks + quantiles scale](https://bl.ocks.org/micahstubbs/536bc140537c1f90bf01f0bb9adc87b8)  
[world map 07 Jenks natural breaks](https://bl.ocks.org/micahstubbs/8fc2a6477f5d731dc97887a958f6826d)  
[world map 08 ckmeans cluster max breaks](https://bl.ocks.org/micahstubbs/9c2397c1da11c7b5d331653bcd475c1f)  
[world map 09 ckmeans cluster min breaks](https://bl.ocks.org/micahstubbs/c7f17dcbdc728e0d579d84e47c33dfa6)  