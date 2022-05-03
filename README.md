# boids
Animating the swarm intelligence of birds

### Running the code
Download the Boids.html file.
Double clicking the HTML file should run in the browser. 
If it does not automatically open in a browswer, right click the file and select 'open with' and choose a browser.

### Tuning the simulation
- width: change the width of the display canvas on HTML
- height: change the height of the display canvas on HTML
- nodeCount: changes how many nodes are simulated. Note: for slower systems, reducing this will improve the frame rate.
- nodeSize: how tall a boid is drawn on the canvas (as a triangle)
- nodeWidth: how wide a boid is drawn on the canvas (as a triangle)
- perceivedDist: how far a given boid can 'see' to determine the cohesion vector
- seperationDist: how far a given boid can 'see' to determine the separation vector
- alignmentDist: how far a given boid can 'see' to determine the alignment vector
- separationWeight: importance of the separation vector (can be any number but a percent is recommended)
- cohesionWeight: importance of the cohesion vector (can be any number but a percent is recommended)
- alignmentWeight: importance of the alignment vector (can be any number but a percent is recommended)
- delta: determines the rate of change to the new recommended orientation (stabilizes abrupt changes to the boid orientation)
