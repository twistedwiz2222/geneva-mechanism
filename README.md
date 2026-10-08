# 3D Printed 6-Slot Geneva Indexing Mechanism

A functional 6-slot Geneva indexing mechanism designed, precision 3D-printed, and metrology-inspected to evaluate dimensional accuracy, kinematically smooth engagement, and physical tolerances.

![Geneva Mechanism Final Assembly](media/assembly_final.jpg)

---

## 🛠️ Project Overview
The Geneva mechanism (Maltese cross) converts continuous rotational motion into precise intermittent rotary indexing motion. This project covers the full engineering workflow: 3D CAD parametric design, FDM additive manufacturing, and post-fabrication metrology verification.

* **CAD Software:** SolidWorks 2026
* **Slicing & Fabrication:** Chitubox / Industrial FDM Slicer
* **Manufacturing Location:** Centre of Excellence in Additive Manufacturing (Room GDN G02)

---

## 📐 Parametric CAD & Feature Specifications

| Feature / Dimension | Nominal CAD Value | Functional Description |
| :--- | :--- | :--- |
| **Overall Assembly Span** | 107.95 mm | Total horizontal center-to-center / base envelope span |
| **Slot Wheel Outer Diameter** | Ø 152.40 mm (R 76.20 mm) | Outer envelope boundary of 6-slot driven wheel |
| **Locking Disc Radius** | R 44.96 mm | Arc holding the wheel stationary during dwell phase |
| **Crank Arm Radius** | 57.19 mm | Effective driving distance from crank axis to pin center |
| **Centre Bore Diameter** | Ø 19.05 mm | Shaft-mounting bore holes for drive and driven shafts |
| **Drive Pin Diameter** | Ø 9.65 mm | Cylindrical drive pin engaging slot for power transmission |
| **Slot Width Feature** | 26.77 mm | Radial slot width guiding drive pin engagement |
| **Assembly Thickness** | 26.77 mm | Overall stacked vertical height of mechanism components |
| **Base Corner Fillet** | R 25.40 mm | Structural baseplate rounding radius |

---

## 🖨️ 3D Printing & Slicing Setup

* **Material:** PLA Thermoplastic Filament (Ø 1.75 mm)
* **Manufacturing Process:** Fused Deposition Modeling (FDM) / Material Extrusion
* **Nozzle Diameter:** 0.40 mm Brass Thermal Nozzle
* **Layer Height:** 0.20 mm
* **Infill Density & Pattern:** 30% Grid Infill
* **Print Speed:** 50 mm/s
* **Temperatures:** Nozzle: 205 °C | Bed: 60 °C

---

## 🔬 Post-Manufacturing Metrology Inspection

Physical measurements were taken in the Precision Measurements and Metrology Laboratory to verify print tolerances against nominal CAD geometry:

| Feature Evaluated | Nominal CAD | Instrument | Measured Value | Evaluation |
| :--- | :--- | :--- | :--- | :--- |
| **Wheel Profile** | R 44.96 mm | Vernier Caliper | R 44.91 mm | Within ±0.1 mm tolerance |
| **Slot Width** | 26.77 mm | Digital Vernier Caliper / Slip Gauges | 26.72 mm | Smooth pin clearance fit |
| **Drive Pin Diameter** | Ø 9.65 mm | Digital Outside Micrometer | Ø 9.62 mm | Precision slip fit verified |
| **Centre Shaft Bores** | Ø 19.05 mm | Dial Bore Gauge | Ø 19.08 mm | Smooth clearance for shaft fit |
| **Fillet Radii** | R 25.40 mm | Radius Gauge Set | R 25.40 mm | Verified profile match |
| **Surface Roughness ($R_a$)** | $R_a$ < 3.2 µm | Stylus Surface Profilometer | $R_a$ = 2.85 µm | Across outer top face |

---

## 👥 Roles & Contributions
* **Kabir Sinha:** FDM setup, slicing configurations, additive manufacturing execution, post-processing, and metrology inspection (caliper, micrometer, surface profilometer).
* **Abhrajit Misra:** 3D solid modeling in SolidWorks, GD&T drawing preparation, and parametric clearance design.
