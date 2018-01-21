# Installation

- Install ReShade https://reshade.me/ (Pro Tip: Railworks uses DirectX 9)

- Download MartinsEffects.ini and put it into the same folder as Railworks.exe

Depth Buffer Issues:

- To access the depth buffer for MXAO you will have to set Railwork's anti-aliasing setting to FXAA or Disabled. I recommend using something like Nvidia's DSR feature to further reduce any jagged edges, the performance impact is surprisingly low from my experience.

- You may need to change RESHADE_DEPTH_INPUT_IS_REVERSED to 0 in the ReShade settings (not the config file!)
