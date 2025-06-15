# 🧬 In Silico Design of a Multi-Epitope Vaccine Against Monkeypox Virus (MPXV)

This repository documents a research project focused on the rational design of a **multi-epitope peptide vaccine** against **Monkeypox virus (MPXV)** using an immunoinformatics-driven approach. The study leverages computational tools to predict immunogenic epitopes, evaluate vaccine safety, and model host-pathogen interactions via molecular docking simulations.

---

## 📁 Details

**Title**: In Silico Design of a Multi-Epitope Vaccine Against Monkeypox Virus  
**Author**: Dhanyashri A/P Guruparan  
**Institution**: Management & Science University (MSU), Malaysia  
**Degree**: Bachelor of Bioinformatics (Hons)  
**Year**: 2023
**Project Type**: Research Project   
**Keywords**: monkeypox, vaccine-design, immunoinformatics, molecular docking, epitope-prediction, patchdock, TLR4, reverse vaccinology

---

## 📌 Project Overview

The unprecedented global resurgence of monkeypox in 2022 highlighted an urgent need for targeted vaccines beyond existing smallpox-derived solutions. This project applies **reverse vaccinology and immunoinformatics** to identify promising epitope candidates and design a **multi-epitope vaccine construct** capable of eliciting robust immune responses against MPXV.

The methodology integrates:
- Protein sequence retrieval
- Antigenicity and virulence prediction
- B-cell, T-cell, and IFN-γ epitope mapping
- Safety assessments (toxicity, allergenicity)
- Docking simulations with the TLR4 human immune receptor

---

## 🎯 Objectives

- Identify highly conserved, surface-accessible MPXV proteins with high antigenicity
- Predict epitopes capable of activating B-cell, CD4+ and CD8+ T-cell responses
- Validate immunogenicity and safety (non-toxic, non-allergenic, IFN-γ inducing)
- Evaluate molecular interaction of vaccine targets with host immune receptor TLR4
- Propose a stable, safe, and immunogenic peptide-based vaccine candidate

---

## 🔧 Tools & Databases Used

| Tool / Database       | Purpose                                                            |
|------------------------|--------------------------------------------------------------------|
| **UniProt**            | Retrieval of MPXV surface-binding protein sequences               |
| **VaxiJen v2.0**       | Antigenicity prediction of full proteins and individual peptides  |
| **VirulentPred**       | Prediction of virulence-associated features                       |
| **IEDB Tools**         | Prediction of linear B-cell, MHC-I, and MHC-II T-cell epitopes    |
| **IFNepitope Server**  | Identification of IFN-γ inducing peptides                        |
| **PatchDock & IGemDocks** | Docking of epitope structures with human TLR4 receptor         |

---

## 🔬 Key Findings

- **Protein Targets Selected**: A33R, H3L, M1R, and L1R surface-binding proteins of MPXV.
- **Antigenicity Scores** (VaxiJen ≥ 0.4 threshold):  
  - A33R: 0.4775  
  - H3L: 0.4683  
  - M1R: 0.6173  
  - L1R: 0.4085

- **Virulence Scores** (VirulentPred): All proteins scored high in virulence prediction, indicating relevance as immune targets.

- **Epitope Selection**:  
  - 8 B-cell epitopes (≥14 aa), 17 IFN-γ positive epitopes  
  - T-cell epitopes selected based on strong MHC-I (≤0.05 percentile) and MHC-II (≥99 percentile) binding affinities

- **Final Vaccine Construct**:  
  - Integrated B-cell, CD4+, CD8+, and IFN-γ inducing epitopes  
  - Non-toxic, non-allergenic, and high immunogenic potential

- **Docking Analysis**:  
  - **MPXV M1R** showed strongest binding affinity to **TLR4** based on global energy scores  
  - Indicates potential to trigger effective innate immune signaling

---

## ✅ Conclusion

A novel **multi-epitope vaccine candidate** was successfully designed in silico targeting surface proteins of the Monkeypox virus. The candidate combines B-cell, T-cell, and IFN-γ stimulating epitopes predicted to elicit broad immune responses.

> Among all proteins, **MPXV M1R** emerged as the most promising vaccine target due to its high antigenicity and strong molecular docking interaction with the TLR4 immune receptor.

This vaccine construct is computationally validated for **immunogenicity**, **safety**, and **immune receptor binding**, offering a valuable foundation for further laboratory validation and translational development.

---

## 🔭 Future Directions

- Perform **molecular dynamics simulations** to evaluate structural stability of the vaccine
- Conduct **wet-lab experiments** for in vitro/in vivo validation
- Optimize **linker design and adjuvant inclusion** for enhanced delivery
- Assess **population-specific HLA coverage** and cross-protective potential


---

## 📜 License

This project is licensed under the **MIT License**. It is freely available for academic and research use only. Attribution to the author and MSU is required in derivative works.

---

| This work is original and solely belongs to the author (Dhanyashri) and MSU. All materials and results are intended for academic and non-commercial research purposes only.

