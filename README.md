# Installation

- Install ReShade https://reshade.me/ (Pro Tip: Railworks uses DirectX 9)

- Download MartinsEffects.ini and put it into the same folder as Railworks.exe

Depth Buffer Issues:

- To allow MXAO to access the depth buffer you will have to set Railwork's anti-aliasing setting to FXAA or Disabled. I recommend using something like Nvidia's DSR feature (https://www.geforce.com/hardware/technology/dsr/technology) to further reduce any jagged edges. I personally use DSR 2.5x (3440x1440 to 5160x2160) with 33% smoothness.

- You may need to change RESHADE_DEPTH_INPUT_IS_REVERSED to 0 in the ReShade settings (not the config file!)
