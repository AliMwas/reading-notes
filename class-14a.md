# CSS Transforms, Transitions, and Animations

## Transforms
Definition and Usage
The transform property applies a 2D or 3D transformation to an element. This property allows you to rotate, scale, move, skew, etc., elements. 
![css Transform](https://tipsmake.com/data/images/3d-transform-in-css-picture-1-jtznOkrOW.jpg)

## Transitions

CSS transitions allows you to change property values smoothly, over a given duration.

Transitions properties:

transition
transition-delay
transition-duration
transition-property
transition-timing-function


How to Use CSS Transitions?
To create a transition effect, you must specify two things:

the CSS property you want to add an effect to
the duration of the effect.

Specify the Speed Curve of the Transition
The transition-timing-function property specifies the speed curve of the transition effect.

The transition-timing-function property can have the following values:

ease: specifies a transition effect with a slow start, then fast, then end slowly (this is default)
linear: specifies a transition effect with the same speed from start to end
ease-in: specifies a transition effect with a slow start
ease-out: specifies a transition effect with a slow end
ease-in-out: specifies a transition effect with a slow start and end
cubic-bezier(n,n,n,n): lets you define your own values in a cubic-bezier function.

![Transition](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions/transitionsprinciple.png)


## Animations
What are CSS Animations?
An animation lets an element gradually change from one style to another.

You can change as many CSS properties you want, as many times as you want.

To use CSS animation, you must first specify some keyframes for the animation.

Keyframes hold what styles the element will have at certain times.

Delay an Animation
The animation-delay property specifies a delay for the start of an animation.