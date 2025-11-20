# Microfluidic Organ-on-a-Chip System Design

**Note:** For full technical details, flow analysis, design rationale, and fabrication considerations, please refer to the PDF report included in this repository.

This project presents the design, modelling, and documentation of a **microfluidic Organ-on-a-Chip (OoC) system**, including microfluidic layouts for three specific organ models:

- **Heart-on-a-Chip**
  
  <img width="800" height="527" alt="image" src="https://github.com/user-attachments/assets/7936f69e-35d1-41f5-9c35-988b7c3c3ee8" />

- **Liver-on-a-Chip**
  
  <img width="800" height="517" alt="image" src="https://github.com/user-attachments/assets/29055eca-be91-42a8-830e-ec7aedfd6160" />

- **Lung-on-a-Chip**
  
  <img width="800" height="517" alt="image" src="https://github.com/user-attachments/assets/6ede30e5-d7f3-4b46-b1cb-7f51c2b5fd67" />


These devices replicate key microphysiological functions of human tissues by controlling fluid flow, nutrient transport, and microenvironmental conditions in a micro-scaled platform.

---

## Project Overview

Organ-on-a-chip devices aim to mimic human organ behaviour using microfluidic channels and culture chambers. This design project includes:

- CAD models of three OoC devices  
- microchannel network geometry for perfusion  
- cell-culture chamber integration  
- standardized footprint layout (50 mm × 30 mm)  
- technical drawings for fabrication  

These designs can be used for prototyping, soft-lithography fabrication, drug-testing research, or microphysiological modelling.

---

## Repository Contents

| File Name                                | Type | Description |
|------------------------------------------|------|-------------|
| `Heart_on_Chip.step`                     | STEP | CAD model of the heart-on-a-chip device. |
| `Liver_on_Chip.step`                     | STEP | CAD model of the liver-on-a-chip device. |
| `Lung_on_Chip.step`                      | STEP | CAD model of the lung-on-a-chip device. |
| `Heart_on_Chip.stl`                      | STL  | Mesh model for printing/simulation. |
| `Liver_on_Chip.stl`                      | STL  | Mesh model for printing/simulation. |
| `Lung_on_Chip.stl`                       | STL  | Mesh model for printing/simulation. |
| `Heart_Technical_Drawing.pdf`            | PDF  | Fabrication drawing for heart-on-a-chip. |
| `Liver_Technical_Drawing.pdf`            | PDF  | Fabrication drawing for liver-on-a-chip. |
| `Lung_Technical_Drawing.pdf`             | PDF  | Fabrication drawing for lung-on-a-chip. |
| Project Report (PDF)                     | PDF  | Complete documentation of methodology, design reasoning, and constraints. |

---

## Design Goals

The system was designed to satisfy several key microphysiological engineering criteria:

### ✔ Controlled Laminar Flow  
Microchannels are sized to maintain laminar flow (Re < 1000) suitable for nutrient perfusion.

### ✔ Physiologically Relevant Shear Stress  
Channel height, width, and flow rate are chosen to produce shear stress levels appropriate for each organ type.

### ✔ Biocompatible Chamber Geometry  
Chambers allow for proper cell adhesion, media exchange, and optional membrane integration.

### ✔ Fabrication Compatibility  
Dimensions, fillets, and tolerances are tuned for:
- Soft-lithography (PDMS molding)
- CNC micromachining
- Laser micro-patterning

---

## Organ-Specific Designs

Each organ chip has a standardized device footprint (50 mm × 30 mm) but a unique internal microchannel architecture reflecting organ-specific physiological features.

---

## **Heart-on-a-Chip**

The heart chip contains a symmetrical channel geometry designed to support rhythmic fluid oscillation or unidirectional perfusion for cardiomyocyte cultures.

Key features:
- Concentric microchannels allowing nutrient diffusion
- Central chamber for cell seeding
- Designed depth suitable for monolayer or thin-tissue constructs

**Insert Heart Image Here**

---

## **Liver-on-a-Chip**

The liver chip includes a multi-branch sinusoid-like channel layout inspired by hepatic microarchitecture. This design supports:

- Parallel microchannel array for high-surface-area perfusion  
- Gradients of nutrients/toxins corresponding to zone 1 → zone 3 liver behaviour  
- A large rectangular culture chamber with controlled inflow/outflow geometry  

**Insert Liver Image Here**

---

## **Lung-on-a-Chip**

The lung chip includes a dual-chamber and branching network that models alveolar interface behaviour. Features include:

- Compartmentalized zones for air and media  
- Thin planar region for potential membrane integration  
- Distributed microchannels to mimic alveolar perfusion patterns  

**Insert Lung Image Here**

---

## Design Workflow

1. **Organ Modelling Requirements**  
   Physiological parameters (shear stress, flow rate, oxygenation, chamber volume) were extracted for each organ.

2. **Microchannel Layout Creation**  
   Channel patterns were sketched based on biological analogues:  
   - Cardiac microvasculature  
   - Hepatic sinusoids  
   - Alveolar branching structures  

3. **CAD Development**  
   Complete 3D models were constructed using a standardized footprint.

4. **Technical Drawings**  
   Each chip has a linked technical drawing defining:
   - All planar dimensions  
   - Channel depths and widths  
   - Tolerances  
   - Section views  

5. **Manufacturing Preparation**  
   Geometry was exported in STEP/STL formats for:
   - PDMS mold fabrication  
   - 3D printing prototypes  
   - Micro-CNC machining  

---

## Applications

These organ-on-a-chip devices can be used for:

- Drug metabolism and toxicity studies  
- Microphysiological system development  
- Multi-organ biological pathway simulation  
- Biomedical engineering education and research  
- Cell-culture flow experiments  

---

## How to Use the Files

### STEP Files  
For editing, integration, and simulation in CAD tools such as:
- SolidWorks  
- Fusion 360  
- CATIA  
- FreeCAD  

### STL Files  
For:
- 3D printing molds  
- Mesh-based CFD  
- Direct visualization  

### PDF Drawings  
For fabrication reference.

---

