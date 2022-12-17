# U3D-Sea
A 3D Sea made in Unity3D with **Gerstner Waves**, followed the YouTube tutorial: https://www.youtube.com/watch?v=yqCHiZrgKzs  
The Build folder contains my Sea Demo that can run by clicking the .exe file.  
The Asset folder contains a material named **M_Sea** for a plane(The sea surface) and the shadergraph named **Shader_Sea**, set **M_Sea** to be the material for a plane object and set the shader of **M_Sea** to be **Shader_Sea** if it's not.  
Once **Shader_Sea** requires two Texture 2D Normal map for the sea surface at *Water01* and *Water02* in **WaterParameters**, and a Default Texture 2D for the foam at *Foam Texture* in **Edge Foam Parameters**. Tune other parameters to get your expected effect.
