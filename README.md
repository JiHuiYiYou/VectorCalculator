# VectorCalculator (矢量计算器)

A single-file HTML5 vector calculator supporting 2D/3D vector decomposition, force resolution, and vector arithmetic with real-time interactive visualization.

## Features

### Module 1: Vector Decomposition (矢量分解)
- Input (x, y [, z]) components → outputs magnitude and angle
- 2D: angle from X-axis using atan2
- 3D: spherical coordinates (polar angle from Z-axis)

### Module 2: Force Resolution (合力分解)
- Input magnitude + angle(s) → outputs Fx, Fy [, Fz] components
- 2D: single angle from X-axis
- 3D: polar angle + azimuthal angle

### Module 3: Vector Operations (矢量运算)
- Two-vector arithmetic: A+B, A−B, dot product, cross product (3D), magnitude, angle between vectors
- Parallelogram law visualization for addition/subtraction

### 3D Visualization
- Switch between 2D and 3D modes via the toggle button
- 3D mode features rotatable perspective view with X/Y/Z axes
- Click and drag on any canvas to orbit the 3D view
- Depth-based transparency for better spatial perception
- Projection lines showing vector relationships to coordinate planes

## Usage

Open `矢量计算器.html` directly in a browser. No build step or server required.

**Dependencies (CDN):**
- Tailwind CSS
- Font Awesome 6

Internet connection required for styling.

## Tech Stack

- Vanilla HTML/CSS/JavaScript
- Canvas 2D API for all rendering (2D and 3D projections)
- Custom 3D projection with orbit controls (no Three.js dependency)
