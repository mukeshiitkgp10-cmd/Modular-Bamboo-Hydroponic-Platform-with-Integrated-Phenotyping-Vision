# Modular Bamboo Hydroponic Platform with Integrated Phenotyping Vision

A circular, closed-loop hydroponics platform designed with natural bamboo growth streams, overhead focused grow-lighting, automated nutrient recirculation, and an integrated multi-camera Raspberry Pi phenotyping rig.

---

## Technical Specifications

| Subsystem | Engineering Dimensions / Details |
| :--- | :--- |
| **Upper Growth Stream** | 100 cm length, 15 cm outer diameter, 10 mm wall thickness |
| **Nutrient Reservoir** | 100 cm length, 15 cm outer diameter, 10 mm wall thickness |
| **Crop Module** | 5 net pots with 10 cm *Ocimum basilicum* (sweet basil) |
| **Overhead Board** | 100 cm × 25 cm × 2 cm timber plank |
| **Grow Lighting** | Focused aluminum reflector hood + full-spectrum LED, 50 cm above canopy |
| **Structural Frame** | Dual vertical wooden lateral end-plates (1.15 m × 0.28 m × 2 cm) |
| **Vision Tracking** | 3 nadir-mounted top cameras + 2 axial side cameras (Raspberry Pi) |
| **Power Control** | Submersible pump and external MFC power-switching interface |

---

## 3D Model & Renders

- **Interactive 3D Model:** [`assets/bamboo_rig_model.glb`](assets/bamboo_rig_model.glb)
- **Side Elevation Render:** [`assets/side_profile_render.png`](assets/side_profile_render.png)

---

## Automated Blender 3.6 Script

The complete model, materials, and isometric/side-elevation camera positions are generated parametrically. To reproduce:
1. Open **Blender 3.6 LTS**.
2. Open the **Scripting** tab, paste [`scripts/build_rig.py`](scripts/build_rig.py), and run the script.
3. Press `F12` to render the profile view.
