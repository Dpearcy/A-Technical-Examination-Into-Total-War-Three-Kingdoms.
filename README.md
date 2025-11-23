# A-Technical-Examination-Into-Total-War-Three-Kingdoms.
A Technical Examination Into Total War Three Kingdoms  Exploring Ray Tracing Possibilities for Lighting and Reflections

This is Technical QA report looking a Total War three Kingdoms. 
This use RenderDoc and look at the Pixel shader for GI and Explore can we add Ray tracing to the Randering pipeline 

The report examines how Total War: Three Kingdoms implements lighting and global illumination, evaluates whether ray tracing could be integrated into the game’s rendering pipeline, and outlines the expected performance impact and QA considerations, including potential defects and test strategies.

The scope of this analysis is limited by the following constraints:
•	No access to Creative Assembly’s internal documentation or developers; all information about the rendering pipeline is inferred from graphics knowledge and frame captures.
•	Observations are based solely on the production release build of Total War: Three Kingdoms.
•	No modification of the game’s engine or source code is performed; ray-tracing feasibility is evaluated theoretically, not implemented.

