# Vertex Commands  

Vertex Commands are divided into two categories: **Select Commands** and **Modify Commands**. These tools allow for precise vertex selection and manipulation within your 3D mesh.  

## Select Commands  

### Select All Connected  
- Selects all vertices belonging to the same object if one or more vertices are already selected.  

### Select None  
- Deselects all currently selected vertices.  

### Invert Selection  
- Reverses the current selection for selected objects, selecting all unselected vertices and deselecting the currently selected ones.  

### Grow Selection  
- Expands the current selection by including all vertices directly connected to the currently selected vertices.  

### Shrink Selection  
- Reduces the current selection by removing the outermost vertices from the selection set.  

### Select Holes  
- Selects vertices located on the edges of any holes within the mesh.  

## Modify Commands  

### Collapse Vertices  
- Merges selected vertices into a single point, effectively removing edges and faces between them.  

### Remove Duplicates  
- Deletes overlapping vertices and merges them into a single vertex while maintaining the mesh structure.  

### Split Vertices  
- Separates the selected vertices into independent points, allowing connected faces to detach from one another.  

### Delete Vertex  
- Removes the selected vertex. This operation also deletes any edges and faces that depend on the deleted vertex.  

### Add Faces  
- Attempts to create edges and faces between selected vertices to fill gaps in the mesh.  

### Connect Vertices  
- Adds an edge between two selected vertices, subdividing the face they share.  

### Set Pivot  
- Moves the object’s pivot point to the selected vertex or the average position of multiple selected vertices.  

### Move/Rotate/Scale  
- Enables precise transformations of selected vertices by entering numeric values for movement, rotation, or scaling.  