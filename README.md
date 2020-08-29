# 3D Hover Effect for WEB

Have you seen these amazing 3D hover effect on Apple TV? Now you can easily make the same effect on web page. Just like that.

![Apple TV 3D Hover Effect](/cover.png)

## Three simple steps
1. [Downoload it](https://raw.githubusercontent.com/Volorf/SparklinerJS/master/sparkliner.js);
2. Add `hover3D.js` to your page;
3. Create a new `Hover3D()` instance and set it up.

**When you did it you can get something like this:**

![SparklinerJS](/sparkliner.png)

🔥[Live demo](https://volorf.github.io/SparklinerJS/)

## How to add hover3D.js to my page
Put a hover3D.js link in the `<head>` section. 
Add a script with settings above the closing `</body>` tag.

```html
<!-- A 3d-hover-effect link -->
<script src="js/hover3D.js"></script>
</head>

<!-- A user's hover3D settings -->
<script src="js/my-script.js"></script>
</body>
```

## How to create 3D hover effect
Easy and quick. I'm not kidding.
```javascript
// Create a HoverEffect object and pass an id/className
// of HTML element(s) you want to create the effect to.
let myHover3D = new Hover3D(".card");
```
## How to customize it
You have a bunch of properties you can tweak to control the effect.
```javascript
// X-axis offset
myHover3D.xOffset = 3
// Y-axis offset
myHover3D.yOffset = 3
// Attack. How fast the effect reacts to cursor movement
myHover3D.attack = 0.1
// Release. How fast an element repairs its initial state
myHover3D.release = 0.5
```


## Links
[Linkedin](https://www.linkedin.com/in/oleg-frolov-6a6a4752/) | [Dribbble](https://dribbble.com/Volorf) | [Twitter](https://www.twitter.com/volorf)

