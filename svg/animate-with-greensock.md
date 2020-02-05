# Animation with GreenSock

## GreenSock Overview

> The GreenSock Animation Platform \(GSAP\) animates anything JavaScript can touch \(CSS properties, SVG, React, canvas, generic objects, whatever\) and solves countless browser inconsistencies, all with blazing speed \(up to 20x faster than jQuery\). See why GSAP is used by almost 10,000,000 sites and many major brands.

* [GreenSock Official Website](https://greensock.com/)
* See overview video, [GSAP Visual Overview](https://greensock.com/docs/v3/GSAP)

## What is a tween?

> A Tween is what does all the animation work - think of it like a high-performance property setter. You feed in targets \(the objects you want to animate\), a duration, and any properties you want to animate and when its playhead moves to a new position, it figures out what the property values should be at that point applies them accordingly.

* [Tween on GreenSock docs](https://greensock.com/docs/v3/GSAP/Tween)

## Setup

```text
https://cdnjs.cloudflare.com/ajax/libs/gsap/3.1.1/gsap.min.js
```

* [Add GSAP library](https://codepen.io/manikoth/pen/xxbvNve)

## Basic Tween

Basic tween with `to()` method

```text
  gsap.METHOD( 'HTML TARGET ', { OPTIONS }  )
```

* [Basic Tween](https://codepen.io/manikoth/pen/WNbVqeZ)
* \[Reference `to` method\]\([https://greensock.com/docs/v3/GSAP/gsap.to\(](https://greensock.com/docs/v3/GSAP/gsap.to%28)\)\)

## Example

* [Animating with Stagger](https://codepen.io/manikoth/pen/rNaXJrr?editors=0010)

