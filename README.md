# WebGL Weekly 6

A Three.js living-room scene with an open-front room, upholstered chair, television and console, side table, reading lamp, and two framed windows overlooking a daytime landscape. Orbit around the room to inspect the layout and lighting.

## Run locally

Because the project uses JavaScript modules, open it through a local web server instead of opening the HTML file directly.

From the project directory, run:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000/weekly6.html](http://localhost:8000/weekly6.html) in a browser.

You can also use the Live Server extension in VS Code.

## Controls

- Drag to orbit around the scene.
- Scroll to zoom.
- Resize the browser window to update the camera and renderer. The scene also adapts to smaller screens.

## Project files

- [`weekly6.html`](weekly6.html) loads the scene and defines the import map for Three.js.
- [`weekly6.js`](weekly6.js) creates the room, furniture, exterior view, lighting, controls, and render loop.

## Technologies

- [Three.js](https://threejs.org/) `0.160.0`
- JavaScript ES modules
- WebGL

## Questions
1. What lighting choices make a room feel cozy?  
low, warm light so that the shadows are more present & there isn't a bright light covering everything.
2. What colors feel warm?  
Orange, deep yellow, some red.
3. How does the lamp affect the mood?  
it adds a second light source to add to the evening mood.
4. Why does the room feel more dramatic?  
less light & more shadows + lack of information from the dark.
5. How does darkness affect mood?  
less vibrance is tied to a more chill vibe as there's less color & light coming at you.
6. Why is blue often used in nighttime scenes?  
it's a colder color & is usually the color of the night sky
7. Why do sudden lighting changes feel dramatic?  
because typically, relaxed scenes don't suddenly change their lighting suddenly, like with lightning here.
8. Which objects catch the lightning best?  
Probably the chair & floor as they are affected the most.
9. How does shadow intensity change?.  
It gets lit up spontaniously, meaning shadows increase greatly before going away just as fast.