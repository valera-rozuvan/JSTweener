# JSTweener

Javascript Tweener for Animation. Originally by:

```
Yuichi Tateno (secondlife)
<hotchpotch@N0!spam@gmail.com> | https://github.com/hotchpotch | http://rails2u.com/
```

## About

JSTweener is tween library for JavaScript. JSTweener's API like [Tweener](https://code.google.com/archive/p/tweener/) ([archive](https://web.archive.org/web/20110714013056/http://code.google.com/p/tweener/)).

JSTweener's transitions is Tweener's easing functions (Penner's Easing Equations) porting to JavaScript. See [Tweener Documentation: Transition Types](http://hosted.zeh.com.br/tweener/docs/en-us/misc/transitions.html) ([archive](https://web.archive.org/web/20110714013056/http://hosted.zeh.com.br/tweener/docs/en-us/misc/transitions.html)).

## Examples

```
JSTweener.addTween(element.style, {
  time: 3,
  transition: 'linear',
  onComplete: function() {},
  width: 200,
  height: 200,
  left: 500,
  top: 300
});
```
