# Object Commands  

Object Commands are divided into two categories: **Select Commands** and **Modify Commands**. These tools allow you to manage and transform objects within your scene efficiently.  

## Select Commands  

### Select All  
- Selects all visible objects in the scene.  

### Select None  
- Deselects all currently selected objects.  

### Invert Selection  
- Reverses the current selection, selecting all visible objects that were not previously selected and deselecting the ones that were.  

## Modify Commands  

### Subdivide  
- **Subdivide All Faces:** Divides each face of the selected object(s) into smaller faces, increasing mesh detail.  
- **Catmull-Clark Subdivide:** Applies a smoothing algorithm to subdivide faces while maintaining curvature for a smoother appearance.  

### Duplicate  
- Creates an exact copy of the selected object(s). The duplicated object(s) will appear in the same position as the original but can be moved or modified independently.  

### Mirror Object  
- Flips the selected object(s) along the specified axis (X, Y, Z, or any combination). The mirrored object remains editable.  

### Delete Object  
- Deletes the selected object(s) from the scene.  

### Merge Object  
- Combines two or more selected objects into a single object. Mesh elements are preserved but unified under one object entry.  

### Convert to Tri/Quads  
- **Triangulate:** Converts all faces into triangular polygons.  
- **Convert to Quads:** Combines triangular faces into quad polygons where possible, simplifying the mesh.  

### Adjust Normals  
- **Flip Normals:** Reverses the direction of the face normals, useful for correcting inside-out faces.  
- **Conform Normals:** Ensures all face normals are oriented consistently outward or inward.  

### Boolean (Experimental)  
Boolean operations allow complex shape creation by combining or subtracting objects.  
- **Union:** Combines two objects into a single shape that encompasses both.  
- **Intersect:** Keeps only the overlapping volume of the two objects.  
- **Subtract:** Removes the volume of one object from another.  

### Center Pivot  
- Moves the pivot point of the object to the geometric center of its bounding box, making transformations more predictable.  

### Freeze Transform  
- Applies all current transformations (Move, Rotate, Scale) to the object’s mesh, resetting its transformation values to standard defaults while preserving its appearance.  

### Move/Rotate/Scale  
- Allows precise transformations by entering numeric values for movement, rotation, or scaling directly.  

### Set Shading  
- **Shade Smooth:** Renders the object with smooth shading for a seamless appearance.  
- **Shade Flat:** Renders the object with flat shading, highlighting individual faces.  
- **Shade Autosmooth:** Applies smooth shading based on the angle between adjacent faces, providing a balance between smoothness and detail.  