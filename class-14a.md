# CSS Transforms
The transform property allows you to visually manipulate an element by skewing, rotating, translating, or scaling:
```
.element {
  width: 20px;
  height: 20px;
  transform: scale(20);
} 
```
Even with a declared height and width, this element will now be scaled to twenty times its original size.

**Values**

+ scale(): Affects the size of the element. This also applies to the font-size, padding, height, and width of an element, too. It’s also a a shorthand function for the scaleX and scaleY functions.
+ skewX() and skewY(): Tilts an element to the left or right, like turning a rectangle into a parallelogram. skew() is a shorthand that combines skewX() and skewY by accepting both values.
+ translate(): Moves an element sideways or up and down.  
rotate(): Rotates the element clockwise from its current position.
+ matrix(): A function that is probably not intended to be written by hand, but combines all transforms into one.
+ perspective(): Doesn’t affect the element itself, but affects the transforms of descendent elements’ 3D transforms, allowing them all to have a consistent depth perspective.
---
# CSS Transitions
CSS transitions allows you to change property values smoothly, over a given duration, mouse over the element below to see a CSS transition effect.
```
div {
  transition: width 2s, height 4s;
}
```
properties:
+ transition
+ transition-delay
+ transition-duration
+ transition-property
+ transition-timing-function
--- 
# CSS Animations
An animation lets an element gradually change from one style to another. You can change as many CSS properties you want, as many times as you want. To use CSS animation, you must first specify some keyframes for the animation. Keyframes hold what styles the element will have at certain times.
```
/* @keyframes duration | easing-function | delay |
iteration-count | direction | fill-mode | play-state | name */
animation: 3s ease-in 1s 2 reverse both paused slidein;

/* @keyframes name | duration | easing-function | delay */
animation: slidein 3s linear 1s;

/* @keyframes name | duration */
animation: slidein 3s;
```
This property is a shorthand for the following CSS properties:
+ animation-delay
+ animation-direction
+ animation-duration
+ animation-fill-mode
+ animation-iteration-count
+ animation-name
+ animation-play-state
+ animation-timing-function