
**Status:** ⚠️ **The complete code will be released upon paper acceptance** ⚠️

 # Dynamic Virtual Simulation with Real-time Haptic Feedback for Robotic Internal Mammary Artery Harvesting 

[Shuo Wang](https://orcid.org/0009-0008-6187-0401)<sup>1</sup>,
[Tong Ren](https://orcid.org/0009-0002-1929-8444)<sup>2</sup>,
[Nan Cheng]<sup>2</sup>,
[Rong Wang]<sup>2</sup>,
[Li Zhang](https://orcid.org/0000-0003-3633-9578)<sup>1*</sup>

<sup>1</sup>Tsinghua University, <sup>2</sup>The Six medical center of PLA General Hospital

[[Project](#)] [[arXiv](https://www.preprints.org/manuscript/202502.0335)] [[Video](https://www.youtube.com/playlist?list=PL6KpB8HbHVTTqnfAiExECcJxQTmd1E16l)] [[Supp](#)]
- 📖 [Read the Paper (PDF)](assets/Dynamic%20Virtual%20Simulation%20with%20Real-time%20Haptic%20Feedback%20for%20Robotic%20Internal%20Mammary%20Artery%20Harvesting.pdf)

This repository contains the official implementation of our paper "Dynamic Virtual Simulation with Real-time Haptic Feedback for Robotic Internal Mammary Artery Harvesting", submitted to bioengineering.

**Note:** 
- <span style="color: red">The complete code will be released upon paper acceptance.</span>

## Features
<p align="center">
  <img src="assets/VirtualSurgicalSimulation Platform.png" alt="Hardware configuration of the virtual simulation platform">
</p>
- Topology-preserving cutting algorithm
<p align="center">
  <img src="assets/video1.gif" width="600" alt="Video Abstract">
</p>
- Bidirectional tissue coupling mechanism
<p align="center">
  <img src="assets/video2.gif" width="600" alt="Video Abstract">
</p>
- Dual-channel haptic feedback
<p align="center">
  <img src="assets/video3.gif" width="600" alt="Video Abstract">
</p>
- Dynamic cardiac model integration
<p align="center">
  <img src="assets/video4.gif" width="600" alt="Video Abstract">
</p>



## Requirements
### System Requirements
- Windows/Linux/MacOS
- OpenGL support
- C++ compiler with C++11 support

### Dependencies
- iMSTK (Interactive Medical Simulation Toolkit)
- VTK 
- OpenHaptics (for haptic device support)
- OpenGL
- Eigen

## Key Components
### Physics Simulation
- Position-based dynamics for soft tissue deformation
- Multi-layer anatomical structure simulation
- Connective tissue modeling with strand-based approach
- Collision detection and response

### Surgical Interactions
- Dual haptic device control
- Grasping and cutting mechanics
- Force feedback
- Tool-tissue interactions

### Visualization
- PBR material support
- Multi-layer transparency
- Dynamic lighting
- Real-time force visualization
- 
## Controls
### Keyboard Controls
- `1`: Toggle fascia visibility
- `2`: Switch fascia rendering mode (PBR/Phong)
- `3`: Toggle fat layer visibility
- `4`: Toggle connective tissue strands
- `5`: Remove connective tissue
- `6`: Toggle surgical instruments
- `7`: Toggle environment map
- `8`: Toggle IMA visibility
- `9`: Activate cutting
- `0`: Cut connective tissue
- Space: Play/Pause simulation
- ESC: Exit

### Haptic Device Controls
- Device movement: Control surgical tools
- Primary button: Grasp tissue
- Secondary button: Cut tissue

## Important Notes
- Haptic device support is optional and controlled by `USE_HAPTICS` flag
- Performance depends on mesh resolution and solver parameters
- Real-time performance requires proper hardware support

## Citation
If you find our work useful in your research, please consider to cite our paper:
```

```


## Relevant Works

## Acknowledgement


