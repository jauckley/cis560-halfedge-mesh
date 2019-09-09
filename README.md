# Halfedge Mesh data structure
This is a computer graphics project that uses interlinked pointers in C++ to create an interactive Halfedge Mesh data structure. It is rendered using OpenGL vertex buffers and a polar spherical camera. 
I implemented a GUI to perform various mesh topology editing operations real time, including splitting edges, face
triangulation, Catmull-Clark Subdivision, and extruding faces. I also created an interactive skeleton with transformable joints that can be bound to a mesh’s vertices to allow linear skin deformation.

This project was for a course at the University of Pennsylvania, so the code cannot be publicly displayed due to academic integrity policies. Recruiters interested in the specifics of my work can contact me at jauckley@seas.upenn.edu.

Here are some images to showcase a few features: 

In this image I have loaded an OBJ file of a dodecahedron, rendered with Lambertian shading-
![alt text](https://github.com/jauckley/cis560-halfedge-mesh/blob/master/images/dodeca.png)

Here I extruded each face of the geometry-
![alt text](https://github.com/jauckley/cis560-halfedge-mesh/blob/master/images/dodeca_extruded.png)

This image shows the result of performing 3 iterations of Catmull-Clark Subdivision on the extruded dodecahedron-
![alt text](https://github.com/jauckley/cis560-halfedge-mesh/blob/master/images/dodeca_subdiv.png)

This is an unaltered rendering of a cow broken into polygons, and joints loaded from a JSON-
![alt text](https://github.com/jauckley/cis560-halfedge-mesh/blob/master/images/cow.png)

Here I have bound each vertex of the cow to the joints and manipulated them to rotate the neck of the cow and its back leg-
![alt text](https://github.com/jauckley/cis560-halfedge-mesh/blob/master/images/cow_rotated.png)
