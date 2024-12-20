# Edge Commands  

Edge Commands are categorized into **Select Commands** and **Modify Commands**, offering advanced tools for selecting and manipulating edges within your 3D mesh.  

## Select Commands  

### Select All  
- Selects all edges in the current object.  

### Select None  
- Deselects all currently selected edges.  

### Invert Selection  
- Reverses the current selection for currently selected objects only, selecting all unselected edges and deselecting the currently selected ones.  

### Grow Selection  
- Expands the current selection by including all edges directly connected to the selected edges.  

### Shrink Selection  
- Reduces the current selection by removing the outermost edges from the selection set.  

### Select Holes  
- Selects edges surrounding any holes in the mesh.  

### Select Edge Loop  
- Selects a continuous ring of edges along a face loop, typically forming a circular or rectangular pattern.  

### Select Edge Ring  
- Selects a parallel sequence of edges across adjacent faces, running perpendicular to the edge loop.  

## Modify Commands  

### Extrude Edges  
- Extends selected edges outward to create new geometry connected to the mesh.  

### Bevel Edges  
- Smooths selected edges by replacing them with a single angled edge of a specified size, creating a chamfered effect. This tool does not support multiple divisions for rounded bevels.  

### Subdivide Edges  
- Splits selected edges into smaller segments, increasing the edge density.  

### Delete Edges  
- Deletes selected edges and any associated faces, leaving gaps in the mesh.  

### Add Faces  
- Attempts to fill gaps by creating new faces along the selected edges.  

### Connect Edges  
- Adds edges between two or more selected edges, subdividing the face(s) they belong to.  

### Insert Edge Loop  
- Adds a new edge loop through the midpoint of adjacent edges, creating additional geometry to refine the mesh.  

### Remove Edge Loop  
- Deletes an entire edge loop while maintaining the surrounding mesh’s shape.  

### Set Pivot  
- Moves the object’s pivot point to the midpoint of the selected edge(s).  

### Move/Rotate/Scale  
- Allows precise transformations of selected edges by entering numeric values for movement, rotation, or scaling.  