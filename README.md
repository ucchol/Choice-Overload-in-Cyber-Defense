# Choice Overload in Cyber Defense

Code, analysis, and datasets for the paper **"Using Choice Overload to Degrade Cyber Attacks"**.  
This repository contains a Colab/Jupyter notebook, CSV data, and scripts to replicate experiments, analyze regret across tasks, and generate figures for:
- **Non-Cyber: Laptop Purchasing**
- **CM: File Exfiltration**
- **CM: NMAP Port Scanning**

## Contents
- `Choice_Overload.csv` — Original dataset from the initial experiment.
- `Updated_Choice_Overload.csv` — Final cleaned dataset used for analysis.
- `IARPA_CO_1A_Asif_Rahman_UTEP.ipynb` — Main analysis notebook (Google Colab/Jupyter).

## How to Run in Google Colab
You can run the notebook directly in Google Colab without installing anything locally:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ucchol/Choice-Overload-in-Cyber-Defense/blob/main/IARPA_CO_1A_Asif_Rahman_UTEP.ipynb)

1. Open the link above.
2. In Colab, click the **folder icon** on the left sidebar.
3. Click **Upload** and select both `Choice_Overload.csv` and `Updated_Choice_Overload.csv`.
4. Run all cells: **Runtime → Run all**.

## How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/ucchol/Choice-Overload-in-Cyber-Defense.git
   cd Choice-Overload-in-Cyber-Defense
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook IARPA_CO_1A_Asif_Rahman_UTEP.ipynb
   ```

## Citation
If you use this code or data, please cite:
> Rahman, A., Natividad, C., Sayed, M.A., Aggarwal, P., & Kiekintveld, C.D. (2025). *Using Choice Overload to Degrade Cyber Attacks*.

## License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

