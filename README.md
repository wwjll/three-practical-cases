# three-practical-cases

# What is this lib?

A lib contains practical use cases using three.js and relative.

# How to run

I hate build up a node project even for simple experiment, so all the examples will be designed as a stand-alone case and simply using live-server to run.

run:

- `git clone https://github.com/wwjll/three-practical-cases.git`
- `npm i`
- `install `live-server` plugin to start`

or you can use online cases.

# Blog

You can read the details in my blog : [juejin](https://juejin.cn/user/46634010687316/posts)

# Introduction

- **Dissolve**
  A simple case to extend three.js shader using `onBeforeCompile` api, you can experience 2 different shaders.

  ![Dissolve](./assets/docs/DissolveEffect.gif)

- **CameraEditor**
  A small case to edit splines for camera, including progress control, generator animation, scissor and viewport, using RAF(requestAnimationFrame) only in camera animation as needed, featuring tween.js easing functions in animation progress and more.
  It is available in low-end laptops running scene complicated like San-Miguel.

  ![CameraEditor](./assets/docs/CameraEditor.gif)

# Examples

- [Dissolve](https://wwjll.github.io/three-practical-cases/examples-io/DissolveEffect.html)
- [CameraEditor](https://wwjll.github.io/three-practical-cases/examples-io/CameraEditor.html)
