# JS 30 days - 01 - JavaScript Drum Kit

---

**EventTarget.addEventListener( )** -

```JS
target.addEventListener(type, listener[, options]);
```

What is DOM? The DOM is a kind of model, and the full name equal to Document Object Model. When you using javascript to select the HTML element, it would inherit the API, This API is ruled by DOM and we call it's the DOM element.  
`window.addEventListener('keydown', playSound);`
In this example, the window interface represents a window containing a DOM document. `playSound` plays the role of listener, once the `keydown`[2] event happend to use `window.addEventlistener`

**Arrow funtion and `this`**
`key => key.addEventListener('transitionend', removeTransition)`
Original function we would type

```JS
function greeting(){
    return 'Hello world!';
}
```

In Arrow function

```JS
var greeting = () => {('Hello world!')}
```

Also, we would save the `return` if you just wanna return the value.

`this.classList.remove('playing');`
In Arrow fuction, this means won't be change when define the object.

## Reference

1. [MDN EventTarget.addEventListener()](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener)
2. [Event reference](https://developer.mozilla.org/en-US/docs/Web/Events)
3. [Arrow function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
