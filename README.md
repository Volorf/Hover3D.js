# Cool 3D hover effect for your awesome web project

Have you seen these amazing 3D hover effect on Apple TV? Have you known that you can easily make similar effect? Just like that!

![Apple TV 3D Hover Effect](/hover3D.gif)

## Three simple steps

1. [Download it](https://raw.githubusercontent.com/Volorf/Hover3D.js/master/hover3D.js);
2. Add `hover3D.js` to your page;
3. Create a new `Hover3D()` instance.

🔥 [Live demo](https://olegfrolov.design/hover3d/)

## How to add hover3D.js to my page

Put a hover3D.js link in the `<head>` section.

```html
<!-- A 3d-hover-effect link -->
<script src="hover3D.js"></script>
</head>
```

## How to create 3D hover effect

It's just a single line of code!

```html
<!-- Create a HoverEffect object and pass an id/className of HTML element(s) you want to create the effect to -->
<script>
    let myHover3D = new Hover3D(".card"); // Yep! That's it.
</script>
</body>
```

## How to customize it

You have a bunch of properties you can tweak to control the effect.

```javascript
// X-axis offset
myHover3D.xOffset = 10;
// Y-axis offset
myHover3D.yOffset = 10;
// Attack. How fast the element reacts to cursor movement
myHover3D.attack = 0.1;
// Release. How fast the element repairs its initial state when your cursor leaves it
myHover3D.release = 0.5;
// Sets the distance between the user and the z=0 plane
myHover3D.perspective = 500;
```

## Links

[Portfolio](https://olegfrolov.design/) | [Linkedin](https://www.linkedin.com/in/oleg-frolov-6a6a4752/) | [Dribbble](https://dribbble.com/Volorf) | [Twitter](https://www.twitter.com/volorf)
