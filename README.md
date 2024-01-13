# JSTweener

javascript tweener for animation

## about

Originally created by Yuichi Tateno.

```
Yuichi Tateno (secondlife)
<hotchpotch@N0!spam@gmail.com> | https://github.com/hotchpotch | http://rails2u.com/
```

JSTweener is a tween library for JavaScript. JSTweener's API is like [Tweener](https://code.google.com/archive/p/tweener/) ([archive link](https://web.archive.org/web/20110714013056/http://code.google.com/p/tweener/)).

JSTweener's transitions are Tweener's easing functions (Penner's Easing Equations) ported to JavaScript. See [Tweener Documentation: Transition Types](http://hosted.zeh.com.br/tweener/docs/en-us/misc/transitions.html) ([archive link](https://web.archive.org/web/20110714013056/http://hosted.zeh.com.br/tweener/docs/en-us/misc/transitions.html)).

## example

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

## live demo

With the help of GitHub pages, you can find a live version of the following 3 examples:

- [Transitions](https://valera-rozuvan.github.io/JSTweener/examples/transitions.html)
- [Motion typo](https://valera-rozuvan.github.io/JSTweener/examples/motion_typo.html)
- [Motion typo bezier](https://valera-rozuvan.github.io/JSTweener/examples/motion_typo_bezier.html)

Source code lives in [examples](./examples) sub-directory of this project.

---

## license

The project `'JSTweener'` is licensed under the MIT License.

See [LICENSE](./LICENSE) for more details.

The latest source code can be retrieved from one of several mirrors:

1. [github.com/valera-rozuvan/JSTweener](https://github.com/valera-rozuvan/JSTweener)

2. [gitlab.com/valera-rozuvan/JSTweener](https://gitlab.com/valera-rozuvan/JSTweener)

3. [git.rozuvan.net/JSTweener](https://git.rozuvan.net/JSTweener)

Copyright (c) 2013-2022 [Valera Rozuvan](https://valera.rozuvan.net/)

Copyright (c) 2007 [Yuichi Tateno](https://github.com/hotchpotch)
