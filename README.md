# 💊 Drug Discovery using Generative Models

This project explores how generative deep learning models can accelerate drug discovery by automatically designing and optimizing new molecular structures. It demonstrates a full pipeline from molecular representation to generation, validation, and optimization.

---

## 🎯 Project Objective

To develop a generative model that creates novel drug-like molecules with desired therapeutic properties. The project introduces:

- Molecular representations (SMILES → SELFIES)
- High-dimensional data handling
- Generative modeling (e.g., RNN or VAE)
- Property-based optimization (e.g., gap energy, dipole moment)
- Validity and drug-likeness evaluation

---

## 📦 Dataset

**Source:** [QM9 Molecular Dataset](https://deepchemdata.s3-us-west-1.amazonaws.com/datasets/qm9.csv)

- Contains ~134k small organic molecules
- Includes SMILES strings and chemical properties such as:
  - HOMO-LUMO gap (`gap`)
  - Dipole moment (`mu`)

---

## ⚙️ Pipeline Overview

1. **Data Preparation**
   - Load QM9 dataset
   - Filter molecules by key properties
   - Convert SMILES to **SELFIES** for robustness

2. **Modeling**
   - Train a **generative model** (e.g., RNN) to learn the molecular grammar
   - Sample novel SELFIES strings and convert them back to SMILES

3. **Validation & Optimization**
   - Filter invalid or non-drug-like molecules
   - Optimize for target properties like lower gap energy

4. **Evaluation**
   - Property distribution comparison
   - Visualization of generated vs real molecule structures

---

## 💻 Technologies Used

- Python
- Pandas / NumPy
- DeepChem
- SELFIES
- RDKit
- TensorFlow / Keras

---

## 📂 How to Run

1. Open the notebook:  
   `drugdiscovery_youssefsaraya.ipynb`

2. Run all cells in order:
   - Load dataset
   - Preprocess and convert molecular formats
   - Train the model
   - Generate and evaluate new drug candidates

---

## 🔍 Sample Output

- ✅ Valid SELFIES → SMILES conversion
- 💊 Molecules with improved gap energy
- 📈 Property histograms and scatter plots

---

## 👤 Author

- **Youssef Saraya** – 320210002

---

## 📄 License

This project is released under the **MIT License**.

---

## 🙌 Acknowledgements

- [DeepChem](https://deepchem.io/)
- [SELFIES](https://github.com/aspuru-guzik-group/selfies)
- [RDKit](https://www.rdkit.org/)
# 💊 Drug Discovery using Generative Models

This project explores how generative deep learning models can accelerate drug discovery by automatically designing and optimizing new molecular structures. It demonstrates a full pipeline from molecular representation to generation, validation, and optimization.

---

## 🎯 Project Objective

To develop a generative model that creates novel drug-like molecules with desired therapeutic properties. The project introduces:

- Molecular representations (SMILES → SELFIES)
- High-dimensional data handling
- Generative modeling (e.g., RNN or VAE)
- Property-based optimization (e.g., gap energy, dipole moment)
- Validity and drug-likeness evaluation

---

## 📦 Dataset

**Source:** [QM9 Molecular Dataset](https://deepchemdata.s3-us-west-1.amazonaws.com/datasets/qm9.csv)

- Contains ~134k small organic molecules
- Includes SMILES strings and chemical properties such as:
  - HOMO-LUMO gap (`gap`)
  - Dipole moment (`mu`)

---

## ⚙️ Pipeline Overview

1. **Data Preparation**
   - Load QM9 dataset
   - Filter molecules by key properties
   - Convert SMILES to **SELFIES** for robustness

2. **Modeling**
   - Train a **generative model** (e.g., RNN) to learn the molecular grammar
   - Sample novel SELFIES strings and convert them back to SMILES

3. **Validation & Optimization**
   - Filter invalid or non-drug-like molecules
   - Optimize for target properties like lower gap energy

4. **Evaluation**
   - Property distribution comparison
   - Visualization of generated vs real molecule structures

---

## 💻 Technologies Used

- Python
- Pandas / NumPy
- DeepChem
- SELFIES
- RDKit
- TensorFlow / Keras

---

## 📂 How to Run

1. Open the notebook:  
   `drugdiscovery_youssefsaraya.ipynb`

2. Run all cells in order:
   - Load dataset
   - Preprocess and convert molecular formats
   - Train the model
   - Generate and evaluate new drug candidates

---

## 🔍 Sample Output

- ✅ Valid SELFIES → SMILES conversion
- 💊 Molecules with improved gap energy
- 📈 Property histograms and scatter plots

---

## 👤 Author

- **Youssef Saraya** – 320210002

---

## 📄 License

This project is released under the **MIT License**.

---

## 🙌 Acknowledgements

- [DeepChem](https://deepchem.io/)
- [SELFIES](https://github.com/aspuru-guzik-group/selfies)
- [RDKit](https://www.rdkit.org/)
