# Animator

A browser-based drawing and animation app built with Gleam for UC Berkeley CS 61A.

[Open Animator](https://zachcoder888.github.io/animator/)

## Drawing tools

- Write a `draw` function and see its paths animate. Adjust Shape and Speed, including reverse playback.
- Pause, resume, scrub the timeline, and replay finished animations.
- Add lines, rectangles, triangles, circles, ellipses, arrows, regular polygons, and stars from the scrollable palette. Each addition generates editable code and can be removed separately.
- Select an individual shape group or the whole drawing, enable Move, and drag it. Reset Position clears the selected offset.
- Create, switch, and delete custom drawings. Code and positions are saved automatically in the current browser.

## Snake Game

1. Make or select a drawing, then switch to **Snake Game**.
2. Choose **Use Drawing as Map** to preview its strokes as obstacles on a 30 by 30 grid.
3. Press **Start** and use the arrow keys or WASD to collect food while avoiding walls, obstacles, and the snake's body.
4. Use **Pause**, **Resume**, or **Restart**. **Back to Drawing** returns to the drawing tools.

The best score is stored separately from the drawing library. Browser data is local to each browser and website origin.

This repository contains the built web app served by GitHub Pages.
