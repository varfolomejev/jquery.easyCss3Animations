jquery.easyCss3Animations plugin
===============

Extend $.easyCss3Animation().


Properties supported:
-----------------

* hideElements : true/false (default false)
* startAnimation : number (default 100); #when to start the animation, 0 when a block in the area of the screen


What it does
-----------------

This plugin allows you to use a variety of effects blocks while scrolling.
For example, I used the css library animate.css


Usage
-----------------

```javascript
    $('.animated').easyCss3Animation({hideElements: true});
```

```html
    <div data-classes="fadeInDown" class="animated">test</div>
```