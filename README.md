#The theoretical documentation of Penn State Integrated Hydrologic Model (PIHM)
 
This is for PIHM++ only. PIHM++ is the latest version of PIHM, the updated version from the PIHM v2.2 that is the stable and widely applied version, and that was released on 2010. 

The design of PIHM++ is going to advance the PIHM to new level:

- Technical improvement
  1. Support the latest implicit Sundial/CVODE solver.
  2. Re-code the program in object-oriented programming method.
  3. More human readable input/output files and filenames.
  5. Support OpenMP and OpenMPI Parrallel computing.
  6. The functions to handle the time-series data, including forcing, LAI, Roughness Length, Boundary Condition, Melt factor.
  7. Speed up the model performance via coding strategies.
  8. Screen output the model status and time-spend.
  4. Fix the bugs in PIHM v2.x.
  
- Model improvement
  1. Change the structure/shape of River.
  2. Add Lakes into the hydrologic process (keep updating).
  3. CMA-ES calibration, with either OpenMP or OpenMPI.
  4. Use the Greem-Ampt method to estimate infiltration.
  5. Add the waterbalance control in elements.
  6. Hourly update the ET and Potential ET.
  7. Model debug mode.
  8. Export model initial condition at specific interval.
  9. Automatic check the range of physical parameters
  