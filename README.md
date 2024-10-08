# <https://inab.github.io/openEBench-widgets>

**Widget's mockup web page for OpenEBench**

- [Technologies](#technologies)
- [Iterations](#iterations)
  1. [Initial mockup](#initial-mockup)
  2. [Evolution I](#evolution-i)
  3. [Evolution II](#evolution-ii)
  4. [Evolution III](#evolution-iii)
  5. [Evolution IV](#evolution-iv)
  6. [Evolution V](#evolution-v)

## Technologies
Only [d3.js](https://d3js.org/) is used to draw all iterations

## Iterations
### Initial mockup
- First idea

![Initial mockup](mockup_pictures/initial.png)

### Evolution I
- Agenttips highlighted on hovering
- Colored plug-in icons

![Evolution I](mockup_pictures/evolution-i.png)

### Evolution II
- Categories summary with tick icons
- Online/Offline uptime plot inside the plug-in agenttip icon
- 200x200, 100x100, 75x75 sizes

![Evolution II](mockup_pictures/evolution-ii-1.png)
![Evolution II](mockup_pictures/evolution-ii-2.png)

### Evolution III
- All arcs now show the metrics summary
- Hide arc stroke lines
- Add mouse click event (and a exit button) to fix the agenttips in the screen

![Evolution III](mockup_pictures/evolution-iii-1.png)
![Evolution III](mockup_pictures/evolution-iii-2.png)


### Evolution IV
- Library isolation
- Customizable widget size
- Fix load html without iframe behaviour
- Fix mime types in Ipad devices
- Improved click behaviour
- Added agenttip information to the empty widget parts
- All data in one JSON

![Evolution IV](mockup_pictures/evolution-iv-1.png)
![Evolution IV](mockup_pictures/evolution-iv-2.png)

### Evolution V
- Added package.json management with development and production deployments
- Refactored d3 to import only used submodules (30 -> 7)
- Webpack
  - Minified javascript with uglifyjs
  - Minified icons with pngquant
  - All files packaged in one js

_No screenshot, only internal changes_

### Evolution VI
-  Use real JSON url data
-  Show extern radius with big sizes
-  Only use agent id in data-id attribute
-  Added Scientific benchmarking badge not available
-  Fixed radius position with odd number of metrics
-  Added radial gradiant to the arcs
-  New badge made from zero
-  Agenttips can be shown to the left of the cursor
-  Agent name as data-id
-  Added agent name title
-  Refactorized and reduce the code

![Evolution VI](mockup_pictures/evolution-vi-1.png)
![Evolution VI](mockup_pictures/evolution-vi-2.png)

