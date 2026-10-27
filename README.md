# NeuroShield
NeuroShield is an educational research project exploring signal processing and the robustness of EEG frequency-band features to noise.
Research Question
How does increasing random noise affect estimated theta, alpha, and beta frequency-band power in a synthetic signal?
Method
The experiment:
1. Generates a 10-second synthetic signal containing 10 Hz and 20 Hz sine waves.
2. Adds Gaussian noise at different noise levels.
3. Estimates power spectral density using Welch’s method.
4. Calculates power in three frequency bands:

 • Theta: 4–8 Hz
• Alpha: 8–13 Hz
• Beta: 13–30 Hz
1. Repeats each noise condition across multiple trials and compares the results.
Tools
• Python
• NumPy
• pandas
• SciPy
• Matplotlib
• Jupyter Notebook
Scientific Scope and Limitations
This experiment uses a synthetic signal, not real patient EEG. It is designed to study signal processing and noise robustness.
It does not diagnose, predict, or prevent stroke. No clinical data or validated medical prediction model is used.
Planned Repository Structure
NeuroShield/
├── notebooks/
│   └── neuroshield_noise_experiment.ipynb
├── results/
│   └── neuroshield_noise_experiment.csv
├── requirements.txt
├── .gitignore
└── README.md
Future Work
• Improve reproducibility and document experiment settings.
• Compare different types and levels of noise.
• Visualize changes in frequency-band power.
• Explore suitable public EEG datasets with careful validation.
Project Status
Early-stage educational research project focused on signal processing, experimentation, and reproducible analysis.
