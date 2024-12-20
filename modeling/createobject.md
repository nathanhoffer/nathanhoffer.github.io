# Create Object  

The **Create Object** button is located in the bottom-right of the Modeling Mode screen, to the right of the Focus button. This feature allows you to add new primitive shapes to your scene. Each primitive includes customizable parameters to fit your specific needs.  

## Available Primitives and Parameters  

### Cube  
A standard 3D cube primitive.  
- **Width:** The size of the cube along the X-axis.  
- **Height:** The size of the cube along the Y-axis.  
- **Depth:** The size of the cube along the Z-axis.  

### Stairs  
A straight staircase structure.  
- **Size X:** The width of the staircase along the X-axis.  
- **Size Y:** The depth of the staircase along the Y-axis.  
- **Size Z:** The total height of the staircase along the Z-axis.  
- **Steps:** The total number of steps in the staircase.  
- **Build Sides:** Whether to include side panels on the staircase structure.  

### Curved Stairs  
A staircase that follows a curved path.  
- **Stair Width:** The width of each individual step.  
- **Height:** The total height of the staircase.  
- **Inner Radius:** The distance from the center to the inner edge of the stairs.  
- **Circumference:** The total arc length of the staircase curve.  
- **Steps:** The total number of steps in the staircase.  
- **Build Sides:** Whether to include side panels on the staircase structure.  

### Prism  
A three-sided or multi-sided geometric shape.  
- **Size X:** The width of the prism along the X-axis.  
- **Size Y:** The depth of the prism along the Y-axis.  
- **Size Z:** The height of the prism along the Z-axis.  

### Plane  
A flat surface that can be subdivided.  
- **Width:** The size of the plane along the X-axis.  
- **Height:** The size of the plane along the Y-axis.  
- **Width Divisions:** The number of subdivisions along the width.  
- **Height Divisions:** The number of subdivisions along the height.  

### Cylinder/Pipe  
A cylindrical or hollow pipe-like shape.  
- **Radius:** The distance from the center to the outer edge.  
- **Height:** The size of the cylinder along the Z-axis.  
- **Axis Divisions:** The number of segments around the circumference.  
- **Height Divisions:** The number of segments along the height.  
- **Pipe Wall Thickness (0 for cylinder):** Defines the thickness of the pipe walls. A value of 0 creates a solid cylinder.  

### Arch  
A curved structure or arc.  
- **Angle:** The total angle of the arch.  
- **Radius:** The distance from the center to the outer edge of the arch.  
- **Width:** The thickness of the arch along the X-axis.  
- **Depth:** The thickness of the arch along the Z-axis.  
- **Radial Subdivisions:** The number of segments that define the curvature of the arch.  
- **Build Inside Faces:** Whether to include the inside surface of the arch.  
- **Build Outside Faces:** Whether to include the outside surface of the arch.  
- **Build Front Faces:** Whether to include the front-facing surface of the arch.  
- **Build Back Faces:** Whether to include the back-facing surface of the arch.  
- **Build End Faces:** Whether to include the end caps of the arch.  

### Torus  
A doughnut-shaped object.  
- **Rows:** The number of subdivisions around the outer ring.  
- **Columns:** The number of subdivisions around the inner ring.  
- **Inner Radius:** The radius of the inner ring.  
- **Outer Radius:** The distance from the center to the outer edge.  
- **Horizontal Circumference:** The proportion of the torus completed horizontally (e.g., 360° for a full torus).  
- **Vertical Circumference:** The proportion of the torus completed vertically.  
- **Shade Smooth:** Whether the torus should appear smooth or faceted.  

### Cone  
A conical shape tapering to a point.  
- **Radius:** The radius of the base.  
- **Height:** The height of the cone along the Z-axis.  
- **Axis Subdivisions:** The number of segments around the base of the cone.  

### Sphere  
A fully rounded 3D object.  
- **Radius:** The size of the sphere from the center to its surface.  
- **Subdivisions:** The number of segments used to create the sphere, affecting its smoothness.  

### Text  
Creates 3D text.  
- **Text:** The string value to display as the text.  
- **Font:** The font used for the text (e.g., Arial, Bodoni, Impact).  
- **Thickness:** The depth of the text along the Z-axis.  
- **Spacing:** The spacing between individual characters.  
- **Rotations:** The rotation of the text along any axis.  
- **Shear:** The slant or skew of the text.  
- **Scale:** The overall size of the text.  

### Image  
Creates a quad mesh using an image loaded from the library.  
- **Load from Library:** Opens a file selection dialog to choose an image. The selected image is applied to the quad mesh as a texture.  
