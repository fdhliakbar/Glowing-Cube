# Glowing Cube Using CSS

### Preview

![previewcube](https://user-images.githubusercontent.com/104522615/188384028-4e143538-c334-40a5-8fbb-a54378bd3f49.png)

> Follow for more content

### HTML

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>3D Cube</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <div class="cube">
    <div class="top"> </div>
    <div class="bottom"> </div>
    <div class="left"> </div>
    <div class="right"> </div>
    <div class="front"> </div>
    <div class="back"> </div>

    </div>
  <div class="shadow">

  </div>
<a href="https://youtu.be/v1o9rZ78Lz0"
   target="blank" style="background:#111 ;color:orange;font-weight:bolder;font-size : 0.15rem;border-radius:5px ; padding:3px;position:fixed;bottom:2px;left : 4px;">
   Github: fdhliakbar
</a>
  </body>
</html>
```

---

### CSS

```html
* { padding: 0; margin: 0; box-sizing: border-box; font-size: 100px; } body {
min-width: 100%; min-height: 100vh; display: flex; align-items: center;
justify-content: center; background: black; perspective: 20em;
perspective-origin: 77px 100px; } /* This Cube */ .cube { position: relative;
transform-style: preserve-3d; display: flex; align-items: center;
justify-content: center; animation: animate 15s linear infinite; } @keyframes
animate { to { transform: rotateY(360deg); } } /* Add to shadow */ .shadow {
position: absolute; background: aqua; width: 2em; height: 2em; transform:
translateZ(-130px) rotateX(90deg) rotateZ(3deg); bottom: 0em; left: 4em;
box-shadow: 0 120px 100px 10px blue, 50px 120px 200px 10px blue; filter:
blur(100px); } .top, .bottom, .left, .right, .front, .back { height: 2em; width:
2em; background: aqua; position: absolute; top: 0; bottom: 0; box-shadow: 0 0
50px 10px blue inset, 0 0 0 2em aqua inset; } .front { transform:
translateZ(1em); } .back { transform: translateZ(-1em); } .top { transform:
translateY(-1em) rotateX(90deg); } .bottom { transform: translateY(1em)
rotateX(90deg); } .right { transform: translateX(1em) rotateY(90deg); } .left {
transform: translateX(-1em) rotateY(90deg); }
```

---

### Please Follow :(

<p align="center">
![mioflu](https://user-images.githubusercontent.com/104522615/188391292-6509c910-be80-4d1e-b7c8-9b7c63f95b5a.gif)
</p>
