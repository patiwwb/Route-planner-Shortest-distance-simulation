# Route-planner-Shortest-distance-simulation

<div align="center">
<img src="map.png" width="600" height="450" />
</div>


In this project,  A* search algorithm is utilized to implement a path planning method.
It is based on OpenStreetMap API.
It searches an optimal path from givin start to end position.



Compile the project but first create a build directory and cd that directory:

mkdir build && cd build


From the build directory run cmake and make :

cmake ..

make



The exe is in the build directory. From within build, you can run the project as follows:

./OSM_A_star_search
Or to specify a map file:

./OSM_A_star_search -f ../<your_osm_file.osm>



The test executable is in the build directory. From build just run this cmd:

./test
