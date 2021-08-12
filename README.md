# JSTweener

JavaScript Tweener for Animation. Originally by Yuichi Tateno.

```
Yuichi Tateno (secondlife)
<hotchpotch@N0!spam@gmail.com> | https://github.com/hotchpotch | http://rails2u.com/
```

## getting latest source

A public git repo is available at [git.rozuvan.net/JSTweener](https://git.rozuvan.net/JSTweener). Several mirrors exist: [mirror 1](https://github.com/valera-rozuvan/JSTweener), [mirror 2](https://gitlab.com/valera-rozuvan/JSTweener).

You can get a local copy by running the command:

```
git clone https://git.rozuvan.net/JSTweener
```

## about

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

- [Transitions](https://valera-rozuvan.github.io/JSTweener/examples/transitions.html)
- [Motion typo](https://valera-rozuvan.github.io/JSTweener/examples/motion_typo.html)
- [Motion typo bezier](https://valera-rozuvan.github.io/JSTweener/examples/motion_typo_bezier.html)

## license

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for more details.

## maintainers

- [Valera Rozuvan](https://valera.rozuvan.net/)
