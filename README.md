🧪 Molecular Property Analysis with RDKit

This project uses RDKit to compute molecular descriptors, neutralize molecular charges, and visualize molecular structures. It is designed for cheminformatics tasks such as drug-likeness evaluation, Lipinski filtering, and compound preprocessing.

📘 Overview
	•	📦 Library: RDKit
	•	🧠 Core Features:
	•	Molecular descriptor computation (LogP, MW, HBA, HBD, TPSA, etc.)
	•	Lipinski Rule of Five checks
	•	Charge neutralization using substructure pattern matching
	•	Molecular visualization with 2D structure rendering

🔬 Features
	•	Lipinski Descriptors:
	•	HBA, HBD, Molecular Weight, LogP, TPSA, and Rotatable Bonds.
	•	Charge Neutralization:
	•	Based on substructure rules adapted from Hans de Winter.
	•	Salt Removal (likely implemented later in the notebook).
	•	Molecular Fingerprinting & Similarity (based on imports).
	•	2D SVG Visualization of chemical structures.

🧰 Technologies Used
	•	RDKit – cheminformatics toolkit
	•	pandas, numpy, seaborn – data handling and plotting
	•	IPython.display.SVG – for molecule rendering
	•	matplotlib – optional for charts
