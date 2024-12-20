# Face Commands  

Face Commands are categorized into **Select Commands** and **Modify Commands**, providing tools for selecting and manipulating faces in your 3D mesh.  

## Select Commands  

### Select All  
- Selects all faces in the current object.  

### Select None  
- Deselects all currently selected faces.  

### Grow Selection  
- Expands the current selection by including all faces adjacent to the selected faces.  

### Shrink Selection  
- Reduces the current selection by deselecting the outermost faces in the selection.  

### Invert Selection  
- Reverses the current selection, selecting unselected faces and deselecting selected ones. This only works for currently selected objects.  

### Select Face Loop  
- Selects a continuous ring of faces along a face loop, typically forming a circular or rectangular pattern.  

### Select Face Ring  
- Selects a parallel sequence of faces across adjacent loops, running perpendicular to the face loop.  

## Modify Commands  

### Extrude Faces  
- Extends selected faces outward to create new geometry connected to the mesh. This can also be achieved using the Gesture Button in combination with the Move Tool.  

### Bevel Faces  
- Smooths selected faces by replacing them with a single angled edge at a specified size. This bevel is limited to one division.  

### Subdivide Faces  
- Divides selected faces into smaller sections, increasing face density for more detailed edits.  

### Delete Faces  
- Deletes selected faces and any dependent geometry such as edges, leaving gaps in the mesh.  

### Detach Faces  
- Separates the selected faces into a new, independent object while maintaining their shape and properties.  

### Merge Faces  
- Combines selected faces into a single face, where possible, simplifying the mesh structure.  

### Triangulate Faces  
- Converts selected faces into triangles by splitting each face into three-sided polygons.  

### Flip Face Edge  
- Adjusts the internal edge of a quad face to change its diagonal direction, affecting the structure and shading.  

### Adjust Normals  
- Alters the direction of face normals:  
  - **Flip Normals:** Reverses the direction of selected face normals.  
  - **Conform Normals:** Aligns all normals consistently outward or inward.  

### Set Pivot  
- Moves the object’s pivot point to the center of the selected face or the average position of multiple selected faces.  

### Move/Rotate/Scale  
- Enables precise transformations of selected faces by entering numeric values for movement, rotation, or scaling.  

### Set Shading  
- Changes the shading of selected faces:  
  - **Smooth:** Renders faces with smooth shading for a seamless appearance.  
  - **Flat:** Renders faces with flat shading, highlighting individual polygons.  
  - **Autosmooth:** Applies smooth shading based on the angle between adjacent faces, using a default threshold of 30 degrees.  
