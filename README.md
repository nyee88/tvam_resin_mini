# TVAM Resin Mini (Ec/Dp First Step)

**Goal:** Start with a tiny table of resin curing parameters — **Ec** (critical dose, mJ/cm²) and **Dp** (penetration depth, µm) at **405 nm** — for a few photoresins.  
We’ll load this table in Colab, look at it, and use it later to choose exposure plans.

**Data to edit:** `data/ec_dp_405nm.csv`  
Columns: `resin_or_source, Ec_mJ_cm2, Dp_um, wavelength_nm, notes`

**Next (after the CSV exists):**
- Open the starter notebook in Colab
- Read the CSV
- Sanity-check units and simple plots
