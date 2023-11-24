# 2xOPN-MegaMod 
 New version 2xOPN expansion module, adding the latest stereo selection circuit, suitable for MegaGRRL Desktop.  

# 2023.11.25
2xOPN MegaMod v0.4 and Mixer v0.2 have passed hardware testing and all functions have been verified. The old version has many problems and is not recommended.  
## 2xOPN MegaMod v0.4 includes the following features:
1. Supports playing single OPN, double OPN, single PSG, and double PSG music. Compatible with PC9801-26K, some arcade machines, ZX-Spectrum Turbo Sound FM, Atari ST, Atari STE VGM format music.Software driver support provided by natalie.  

## 2xOPN Mixer v0.2 includes the following features:  
1. A typical dual op amp driven by a single 5V (take NE5532 as an example), it works well and sounds loud.    
2. Independent volume adjustment knob. Supports adjusting the volume of OPN and SSG, as well as the overall volume of the mixer. The volume of OPLL cannot be adjusted because the volume of OPLL itself is too small. This function is completely normal, and the volumes of each channel will not interfere with each other when adjusting the volume.  
3. SSG can be configured with stereo sound. Use three three-position toggle switches to independently control the stereo channels of each SSG. This function is completely normal and will not affect the volume of OPN and OPLL.
4. SSG stereo mixing circuit. This part is based on the ZX-Spectrum's golden ratio mixing circuit, but I modified the resistor values to provide a more stereo effect.  
5. Stereo FM mixing circuit, especially used for dual OPN music.
6. Fully configurable OPN stereo, switched using a three-position switch.
