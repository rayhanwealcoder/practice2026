# API Reference

## Tween Methods
```js
animate.to(".box", { x: 100, duration: 1, ease: "easeOut" });
 ````

###Timeline
```js
const tl = animate.timeline();
tl.to(".box", { x: 100 }).to(".circle", { y: 50 });
```
### SplitText
```js 
const split = animate.splitText(".headline", { chars: true });
animate.from(split.chars, { opacity: 0, stagger: 0.05 });
````



