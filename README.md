# Harmonic Co-occurrence Network (HCN) Analysis

## Overview
This project explores the **Harmonic Co-occurrence Networks (HCNs)** in music using network analysis. Nodes represent pitch classes (MIDI numbers), and edges signify temporal or harmonic relations between them. The analysis spans multiple genres like rock, jazz, classical, and metal, providing insight into musical structures and patterns.

---

## Motivation
Music theory often treats melody, harmony, and rhythm in isolation. This project bridges these elements using network analysis to uncover relationships across genres, enhancing the understanding of music's internal structure.

---

## Approach

1. **Data Preprocessing**:  
   - Perform **FFT** on audio samples to extract dominant frequencies and map them to MIDI numbers (nodes).
   
2. **Network Creation**:  
   - Create a graph where co-occurring MIDI numbers form edges, producing the **HCN** for each song.
   
3. **Network Analysis**:  
   - Apply metrics like degree distribution, assortativity, and community detection to study network structure.

---

## Results
- 14 out of 48 analyzed songs exhibited **scale-free power-law** distributions.
- **Assortativity coefficients** revealed genre-specific trends, such as negative assortativity in rock and metal.
- **Louvain community detection** identified sub-genres within genres.

---

## Code Execution
The Python notebook (`HCN_Analysis.ipynb`) processes audio files, constructs the HCN, and analyzes its structure using various network metrics. The results are visualized to better understand the underlying musical patterns.

---


