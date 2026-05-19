# Eye-in-Hand Camera Mount for UR10 & Robotic Gripper

This repository contains the open-source 3D design files (STL, 3MF, and STEP) for a rigid, lightweight **Eye-in-Hand Camera Mount** designed for the Universal Robots UR10. 

Mounting a depth camera directly to the robot's wrist enables dynamic, clutter-aware perception—making it ideal for advanced robotic vision applications like bin-picking, collision avoidance, and automated sorting.

## 📸 Component Overview
The assembly consists of two interlocking parts designed for structural rigidity and seamless adjustment:
1. **Part 1 (Camera Mount Base):** Features a large 95.00 mm circular aperture ring to accommodate your sensor/gripper interface and a long integrated mounting arm with standard spacing slots.
2. **Part 2 (Adapter Link):** A dual-counterbored extension bracket that enables adjustable positioning along the main arm to fine-tune the camera's optical viewpoint.

---

## 📂 Repository Structure

```text
├── CAD/
│   ├── Part1_Camera_Base.STEP      # Universal CAD for modification
│   └── Part2_Adapter_Link.STEP
├── 3D_Printing/
│   ├── STL/
│   │   ├── Part1_Camera_Base.stl    # Universal printing format
│   │   └── Part2_Adapter_Link.stl
│   └── 3MF/
│       ├── Part1_Camera_Base.3mf    # Includes unit & orientation data
│       └── Part2_Adapter_Link.3mf
├── LICENSE
└── README.md
