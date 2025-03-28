[![51d8fbaa12f542780aa2f96e74537766.png](https://i.postimg.cc/j2SC7jsy/51d8fbaa12f542780aa2f96e74537766.png)](https://postimg.cc/N9ZghB20)

The purpose of this project is to recreate a crop circle—a vast geometric pattern or set of patterns made in a cereal field. A Python script was developed using an object-oriented approach and employing the NumPy and Matplotlib libraries.

Initially, the pattern to be reproduced and the objectives of the script were defined. Then, the base classes ("Interval", "Renderable", "Transformation", etc.) were implemented, followed by the function classes ("CoupleSplineFunction", "PolynomialFunction") and the transformation classes ("Rotation" and "Translation"). Finally, the "Curve" class was designed to handle the rendering of "Renderable" objects using Matplotlib, as well as the logic for assembling all the shapes and drawing them.

We created a pattern by implementing Lagrange interpolation, cubic splines, and Bézier curves in Python using the NumPy and Matplotlib libraries. This project highlights the use of mathematical algorithms for the creation and precise manipulation of complex geometric shapes while leveraging graphical visualization capabilities.

[![output.png](https://i.postimg.cc/jq93NDcm/output.png)](https://postimg.cc/BtTCfQdB)
