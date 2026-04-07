# atractores
ilustración de 2 atractores extraños

The `index.html` file is a dynamically styled and interactive webpage designed as a retrofuturistic terminal for simulating dynamic systems, specifically visualizing attractors like Lorenz and Rössler. Below is a summary:

### Layout and Styles:
- **Head Section**:
  - Utilizes Google Fonts for futuristic typography (`Orbitron` and `Share Tech Mono`).
  - Styles include:
    - Custom `:root` variables for theming (amber, green, teal, etc.).
    - A dark background with gradients, phosphorescent effects, and glitch animations.
  - The page is responsive and optimized for modern devices.

- **Header Section**:
  - Displays a dynamic terminal title with glitch animations, a clock, and system info (e.g., node and sector).

- **Main Section**:
  - Contains two dynamic system panels for `Lorenz` and `Rössler` attractors:
    - **Unique Panels**:
      - **Lorenz Attractor**: Amber-themed (non-linear dynamics, butterfly shape visualization).
      - **Rössler Attractor**: Green-themed (minimal chaos, spiral Möbius ribbon).
    - **Details**:
      - Classification, topology, and equations are provided.
      - Phosphor simulations in CRT-style canvas for attractor visualization.
      - Metrics (e.g., Lyapunov exponents, fractal dimensions) and operational warnings.

- **Footer Section**:
  - Displays terminal metadata (company, node, access level).

### JavaScript Dynamics:
- **Visual Features**:
  - Dynamic clocks and scrambled hex footer inspired by glitch effects.
  - Glitch text generation corrupts specific content temporarily for aesthetic.

- **Runge-Kutta Integration:**
  - Implements the RK4 method for real-time simulation of ordinary differential equations (ODEs) for the attractors.

- **Canvas Graphics**:
  - Real-time projections for attractors in oblique isometric 3D views.
  - Includes phosphor grain, scanlines, vignette, and noise effects for retro CRT emulation.

### Conclusion:
This file utilizes modern web development techniques (CSS, JS) for an engaging simulation environment themed with chaos and non-linear systems. The attractors’ visualizations run dynamically, enhancing user immersion.
