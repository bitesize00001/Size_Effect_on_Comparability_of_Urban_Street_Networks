# Size_Effect_on_Comparability_of_Urban_Street_Networks

**Journal**: International Journal of Sustainable Development and Planning  
**Published**: October 2021  
**Authors**: Hsiao-Hui Chen*, Udo Dietrich  
 [Link to Publication](https://doi.org/10.18280/ijsdp.160603)

---

##  Overview

This paper investigates the **"size effect"** in urban street network analysis—specifically how the size of the catchment area affects the calculation of commonly used network indicators such as **average node degree**. It highlights the methodological bias introduced by arbitrarily defined catchment areas and proposes a theoretical framework to determine an appropriate area size for consistent and comparable network evaluations.

---

##  Key Contributions

- **Problem Identified**: Arbitrary boundaries in spatial network studies distort network metrics.
- **Solution Proposed**: A mathematical model using idealized grid networks to study the sensitivity of indicators like average node degree to catchment size.
- **Findings**:
  - The size effect is prominent until the catchment area reaches approximately **40–50 times** the average street length.
  - A **minimum size of 2000×2000m²** is suggested to ensure comparability in pedestrian networks.
- **Applications**: Network analysis, urban morphology comparison, mobility studies, spatial accessibility evaluations.

---

##  Methodology

- Constructed a theoretical grid network to isolate the size effect.
- Iteratively expanded catchment areas and calculated average node degree.
- Compared results across varying sizes to determine when indicator values stabilize.
- Validated the model with real-world average street lengths.

---

##  Skills and Concepts Demonstrated

| Topic                         | Application                                                             |
|------------------------------|-------------------------------------------------------------------------|
| Urban network analysis       | Understanding of connectivity, centrality, and catchment boundaries     |
| Theoretical model design     | Use of idealized grid systems for indicator stability testing           |
| Quantitative urban planning  | Guidelines for consistent spatial unit definition in urban studies      |
| Methodological rigor         | Transparent, reproducible indicator behavior analysis                   |
| Spatial thinking             | Scale-dependence and edge/boundary effects in urban system evaluation   |

---

##  Why This Matters

This work is relevant to urban planners, geographers, and data scientists working with:
- **OpenStreetMap / OSMnx**-based modeling
- **Spatial accessibility analysis**
- **Mobility networks**
- **Urban form classification**

It offers not only theoretical clarity but also **practical recommendations** for designing comparable and scalable urban street network studies.

---

##  Repository Structure

size-effect-urban-networks/
│
├── 📄 size_effect.pdf          # Full-text journal article
├── README.md                  # Project overview (you are here)
