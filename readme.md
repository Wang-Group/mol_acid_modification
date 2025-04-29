# Data to Physics in Minutes: An Agentic Large Language Model Solves a Competitive Adsorption Puzzle

This repository accompanies the paper **"Data to Physics in Minutes: An Agentic Large Language Model Solves a Competitive Adsorption Puzzle"**, where we demonstrate how a reasoning-capable LLM autonomously derives a physically meaningful model for competitive adsorption on metal–organic layers (MOLs), outperforming previous empirical approaches.

## 📁 Repository Structure
```plaintext
.
├── content_shared_with_gpt/          # Research summaries and data shared with the LLM
├── chat_history/                     # Record of the chat history with the LLM (chathistory.png)
├── MOL_surface_adsorption_250427.csv # Experimental adsorption data
├── 0-competitive_adsorption.ipynb    # Fits using the literature-based and derived models
├── 0-fitting_with_forms.ipynb        # Fitting using symbolic formula inputs
├── 0-fitting_sterimol.ipynb          # Fitting using the GPT-derived model with Sterimol descriptors
├── 0-result_analysis.ipynb           # Correlation analysis and result interpretation
```
## ⚙️ Prerequisites

This project requires **Python 3.11** and the following Python packages:

- `numpy`
- `scipy`
- `pandas`
- `matplotlib`
- `rdkit`
- `morfeus`
- `scikit-learn`
- `seaborn`

## 🧠 Key Contributions

- Demonstrates autonomous scientific modeling by an LLM from raw data and contextual documents.
- Derives a physically grounded three-parameter competitive adsorption model incorporating structural constraints.
- Benchmarks against previous models and shows improved interpretability and accuracy.

## 📊 Data

The experimental adsorption data for different acid modifiers on MOL surfaces is provided in `MOL_surface_adsorption_250427.csv`.

## 📝 Notebooks Overview

- **0-competitive_adsorption.ipynb**: Compares literature-reported models with our derived model.
- **0-fitting_with_forms.ipynb**: Fits user-specified mathematical formulas to the data.
- **0-fitting_sterimol.ipynb**: Uses Sterimol descriptors and the GPT-derived model for regression.
- **0-result_analysis.ipynb**: Analyzes descriptor correlation and validates the final model.

## 🔗 Citation

If you use this work or code, please cite our paper:

> _[Full citation]_

## 📬 Contact

For questions or collaboration, please contact:  
**Yibin Jiang**  
Email: [yibin_jiang@outlook.com](mailto:yibin_jiang@outlook.com)  
Department of Chemistry and Chemical Engineering, Wang Group, Xiamen University

## License 

MIT license