## javascript-shaders-glsl-3d

### Description

This project is a simple example of how to use shaders in javascript with glsl. The example is a 3D heart that is animated with a glow effect. The heart is created with a quadratic bezier curve formula and a heart formula from mathworld wolfram. The glow effect was created with shadertoy examples. 

### How it works

The javascript is responsible for creating a canvas on the HTML page and initializing the WebGL context. Then, there are the shaders in the form of strings, which are used to render the heart. These shaders are written in the GLSL language, which is specifically designed to work with 3D graphics. However, these shaders are sent to the GPU through WebGL calls from JavaScript.

### Technologies/Tools

- JavaScript 
- HTML 5
- CSS 3
- Quadratic Bezier Curve Formula - <a href="https://www.shadertoy.com/view/MlKcDD">Show</a>
- Mathworld Wolfram Heart Formula - <a href="http://mathworld.wolfram.com/HeartCurve.html">Show</a>
- Glow Effect - <a href="https://www.shadertoy.com/view/3s3GDn">Show</a>


### Instalation

- Clone this project
- Run with browser

### Play

- Click here to run live <a href="https://eduardotks.github.io/javascript-shaders-glsl-3d/heart.html">click</a>

### Image

<p align="center">
			<img src="https://github.com/eduardotks/javascript-shaders-glsl-3d/blob/main/images/Glow.png" style="width: 78%;" alt="Imagem 1">
			<img src="https://github.com/eduardotks/javascript-shaders-glsl-3d/blob/main/images/QuadraticBezier2d.png" style="width: 78%;" alt="Imagem 2">
			<img src="https://github.com/eduardotks/javascript-shaders-glsl-3d/blob/main/images/wolfram%20mathworld.png" style="width: 78%;" alt="Imagem 3">
			<img src="https://github.com/eduardotks/javascript-shaders-glsl-3d/blob/main/images/heart.png" style="width: 78%;" alt="Imagem 4">
</p>
