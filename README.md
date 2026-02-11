Liquid Simulation: Manual Override
A high-performance, browser-based physics sandbox designed for fluid-like particle simulation and interactive nebula mixing. This project utilizes a custom velocity-based engine to simulate thousands of particles in real-time with zero external dependencies.

🚀 Live Demo
To make this project public, follow the hosting instructions below.

✨ Core Features
Real-time Fluid Dynamics: Simulate up to 10,000 particles with custom viscosity and friction settings.
Manual Physics Override: Granular control over internal velocity, interaction force, and particle density.
Multiple Catalyst Modes:
Vortex: Creates orbital swirling patterns around the interaction point.
Burst: Diffuses particles away in high-velocity explosions.
Gravity: Pulls the nebula into a dense singularity at your touch.
Visual Customization: 5 curated color palettes and adjustable trail persistence for "silk-like" mixing effects.
Standalone Export: Built-in tool to export the current lab state as a single portable HTML file.

🛠️ Technical Details
The simulation is built using a Velocity-Verlet inspired integration method:
Viscosity: Calculated as a multiplier on current velocity (V_{new} = V_{old} \times \mu).
Interaction: Force is applied using an inverse-square distance falloff to ensure smooth transitions near the cursor/touch point.
Rendering: Optimized Canvas2D API utilizing fillRect with a low-alpha clear color to generate procedural motion trails without the overhead of WebGL.

📦 Installation & Deployment
Since the entire application is contained within a single file, deployment is instant:

Web Hosting (https://shaijujose308-ux.github.io/Liquid-stimulation-/):
Rename nebula_lab.html to index.html.
Push to a GitHub repository.
Enable GitHub Pages in the repository settings.

🎮 Controls
Click/Touch: Activate the mixing catalyst.
Sidebar Menu: Access the Manual Override panel to adjust physics constants.
Reinitialize: Reset the particle grid to apply new density settings.
__License_
Apache 
Copyright 2024 Nebula Mixing Lab
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at
http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
