#index.html PageSpeed Insight score improvement
1. compress profilepic.jpg and pizzeria.jpg
2. minimize perfmatters.js, print.css, and style.css files
3. inline style
4. add async attribute to javascript
5. minimize index.html

#reduce pizza.html to 60 fps
1. minimize javascript and css files
2. modify the main.js files to remove the coupling of handling onscroll event and changing the DOM and the style values
3. call refreshAnimationFrame in the updatePositions function of main.js
4. call the refreshAnimationFrame only when ticking is false and it is convenient to render the page