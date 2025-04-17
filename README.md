
# 🧠 Stereotaxic Clamp Project

## 📌 Project Intent

This repository documents the design and fabrication of a **stereotaxic clamp system** used in **rodent neurosurgery**. The clamp securely positions a secondary 6 mm rod exactly **1 inch (25.4 mm)** from a primary vertical rod, enabling precise alignment of implants, microinjectors, or electrodes over a mouse skull. Two clamp designs are provided, each available for **CNC machining** and **3D printing**.

The goal is to provide an **accessible, modifiable, and affordable open-source solution** for labs conducting small animal stereotaxic procedures.

---

## 📁 Repository Structure

```
Stereotaxic_Clamp/
├── Design_Files/
│   ├── DesignB/
│   │   ├── CNC/
│   │   │   ├── DesignB_CNC_BOM.xlsx
│   │   │   └── CAD_Files/
│   │   └── 3D_Print/
│   │       ├── DesignB_3DPrinted_BOM.xlsx
│   │       └── STL_Files/
│   │       └── Instructions/
│   │           └── Assembly_Guide.md
│   └── DesignA/
│       ├── CNC/
│       └── 3D_Print/
└── README.md                   # This project overview file
```

---

## 🧩 Designs Overview

- **Design1**: Standard block-style clamp with parallel rod positioning and set screws.
- **Design2**: Alternative geometry clamp, optimized for fixed alignment and simplified printing.

Each design includes:
- Fully dimensioned CAD files (`.STEP`, `.SLDPRT`)
- Ready-to-print STL files (for 3D printing)
- Manufacturing instructions for CNC or SLA
- Detailed BOMs with sourcing links

---

## 📊 Cost Comparison – Design1

| Production Method      | Total Cost (100 Units) | Cost per Part |
|------------------------|------------------------|---------------|
| 3D Printing (In-House) | $133.00                | $1.33         |
| CNC In-House           | $494.44                | $4.94         |
| CNC External Vendor    | $1,124.44              | $11.24        |

---

## 🧑‍🔬 Target Users

- Neuroscience and bioengineering labs using rodent stereotaxic frames
- Researchers needing affordable accessories for small animal surgeries
- Makers and engineers customizing implant tools for preclinical models

---

## 📬 Contributions

Feel free to fork this repo and submit pull requests with design improvements or additional variants. Design2 is ongoing — feedback welcome!

---

## 📜 License

This repository is shared under the MIT License. Attribution appreciated.
