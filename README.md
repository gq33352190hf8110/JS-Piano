# JS Piano

A fun project that i did to demonstrate the power of JS !!

  - You can play any track you want
  - Define as many divs you want to make instances
  - You can define the size of your midi !
  - Style away with the css your unique piano.
  - Listen my demo of coldplay (scientist) -- without even a lesson !!
  - happy playing !

### Installation

You only need to define it on html and js with jquery.

```html
<div class="piano piano-instance-1"></div>
```

```js
$(".piano-instance-1").piano();
```

and you are good to go!

You can also use the tone option to make the piano larger or smaller !

```js
$(".piano-instance-1").piano({
    tone: 3
});
```

### Version
1.0.0
