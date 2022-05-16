# Project Proposal

Jinqi Liu jl12232



I plan to do the Project 3 which is **Interactive Geometry Remeshing**.  And the libraries I may use is libigl, numpy and triangle.



- **Parametrize mesh** into (UV) plane, **triangulate** UV plane nicely, **transfer mesh back to 3D**.
- Design plane triangulation to **minimize post-transfer distortion**
  - Compensate for parametrization’s area distortion:  **vertex density proportional to area scaling**.
  - Detect creases in original mesh, constrain these to be edges in triangulation.
  - Optionally increase sampling in “important regions,” e.g. high curvature.



![image-20220422215617758](C:\Users\82778\AppData\Roaming\Typora\typora-user-images\image-20220422215617758.png)