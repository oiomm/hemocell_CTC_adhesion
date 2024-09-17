# Program and Data Files for the Article:
**A Lattice Boltzmann Study of the Transport and Adhesion of Deformable Circulating Tumor Cells in Bifurcated Microvessels**

## Instructions for Using the Program Files

- Install HemoCell by referring to the official HemoCell link: [https://github.com/UvaCsl/HemoCell](https://github.com/UvaCsl/HemoCell)
- Copy the contents of the `program` folder to `HemoCell/examples/case_bif`.

## Program Files

- **`case_bifurcatedvessel.cpp`** - Main Program:  
  This is the simulation script for the flow and adhesion of a single CTC in a symmetrical bifurcated blood vessel.
  
- **`config.xml`** - Simulation Parameter Configuration File:
  - Sets the number of warm-up iterations for preparing the fluid field.
  - Defines output directories for data storage, logging, and checkpoints.
  - Controls the update frequency of the particle material model and particle positions relative to the fluid time step.
  - Uses an `.stl` file to define the geometry of the simulation domain.
  - Sets fluid density, viscosity, spatial resolution, time step, Reynolds number.
  - Defines particle interaction repulsion constants.
  - Specifies total iterations (`tmax`), data writing, and checkpoint intervals.
  - Configures parameters related to viscosity inside the simulation grid.

- **`CTC.pos`** - CTC count and positions.

- **`CTC.xml`** - Constitutive model parameters for CTC:  
  Describes the geometry and stiffness of the CTC.

- **`tube.stl`** - Geometry file for the blood vessel.

## Data Files

- Standard data format files for ParaView post-processing software, which can be directly imported for viewing.  
  Refer to the ParaView official link: [https://github.com/Kitware/ParaView](https://github.com/Kitware/ParaView)

- Data can be found here ：(https://drive.google.com/file/d/1S2AdW6-yMy9p4g16uwNrXJZ1Hyn5V8h4/view?usp=drive_link)


