# Tweening

## What is a tween?

> A Tween is what does all the animation work - think of it like a high-performance property setter. You feed in targets \(the objects you want to animate\), a duration, and any properties you want to animate and when its playhead moves to a new position, it figures out what the property values should be at that point applies them accordingly.

* [Tween on GreenSock docs](https://greensock.com/docs/v3/GSAP/Tween)

## Basic Tween with Options

* **HTML Elements: targets** - the object\(s\) whose properties you want to animate. This can be selector text like `".class"`, `"#id"`
* **Options for Tweening: vars** - an object containing all the properties/values you want to animate, along with any special properties 
* 🖊️[Tween with Options](https://codepen.io/manikoth/pen/LYVYpjP)

## from\(\)

* gsap.from\(\) animates from the values you specify to the object’s natural values.
* 🖊️[Tween: from\(\)](https://codepen.io/manikoth/pen/gOpOajm?editors=0010)

## fromTo\(\)

* gsap.fromTo\(\) animates ​**from**​ the values you specify **​to​** the values you specify
* from point A to point B
* be explicit and set all options at **from** point a, **to** point b
  * remove `opacity`  at one point. what changes? 
* 🖊️[Tween: fromTo\(\)](https://codepen.io/manikoth/pen/xxGxwQK?editors=0010)

## Delay

* how much time should transpire before animation begins
* 🖊️[Tween: delay property](https://codepen.io/manikoth/pen/QWbWjox?editors=0010)

## Repeat

* `repeat`​: how many times the animation should repeat 
* `yoyo`​: when set to true the animation will play back and forth
* `repeatDelay​`: how much time should transpire between each repeat
* 🖊️[Tween: repeat property](https://codepen.io/manikoth/pen/XWbWmwL?editors=0010)

## Easing

{% hint style="info" %}
[GreenSock Easing Visualizer](https://greensock.com/docs/v3/Eases)
{% endhint %}

* An ease controls the rate of change as your animation plays
* In simple uses an ease will control whether your animation slows down or speeds up. 
* An ease can be applied on the way out \(default\), on the way in, or both directions. 
* The steeper the curve the faster change is taking place.
* 🖊️[Tween: Easing property](https://codepen.io/manikoth/pen/rNVNOXE?editors=0110)

## Stagger

* `stagger` property allows you to offset the start time of multiple targets in a single tween
* GSAP3 you no longer need the staggerTo\(\), staggerFrom\(\), and staggerFromTo\(\) methods of GSAP2.
* 🖊️[Tween: Stagger property](https://codepen.io/manikoth/pen/VwLwevP)

