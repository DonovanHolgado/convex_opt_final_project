# Online Gradient Descent and FTRL: Regret Analysis and Empirical Evaluation

Evaluates Online Gradient Descent (OGD), FTRL-L2, and FTRL-L1 on the 
ELEC2 electricity market dataset and synthetic data.

## Repo Structure

final_project.ipynb       # main notebook with all experiments
figs/
    regret_plot.png       # cumulative regret vs T 
    sweep_plot.png        # hyperparameter sensitivity analysis
    sparsity_plot.png     # FTRL-L1 vs FTRL-L2 sparsity over time
    equivalence_plot.png  # OGD vs FTRL-L2 weight divergence
    adverserial_plot.png  # adversarial experiment O(√T) tightness
README.md

## Requirements
python >= 3.8
numpy
pandas
matplotlib
scikit-learn

Install dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn
```


## Data

The ELEC2 dataset is fetched automatically via scikit-learn's OpenML 
interface. No manual download is required.


## Running the Notebook

Run all cells in order from top to bottom. Each section depends on 
variables defined in previous sections. 


## Author
Donovan Holgado 