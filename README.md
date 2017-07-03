# NVOC

Based on the work done by 2PKAQWTUQM2Q7DJG https://1vwjbxf1wko0yhnr.wordpress.com/author/2pkaqwtuqm2q7djg/  

MultiGPU support added by deathcamp.

Complie with anything (windows only), or download the exectuable.

Usage: nvoc.exe core_offset(+-500) memory_offset(+-500)

Example: nvoc.exe -400 +500 will lower the core clock by 400Mhz and increase the memory clocks by 500Mhz (1000Mhz effective datarate)

Tip: Use NVSMI (NVIDIA-SMI.exe) for power level control; "c:\Program Files\NVIDIA Corporation\NVSMI\nvidia-smi.exe" -pl 100 (set power limit to 100W)

License: DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
