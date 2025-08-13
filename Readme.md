AI-Powered Prediction of Non-Coding Variant Effects
This project analyzes non-coding genetic variants by generating a 1M base pair synthetic genome, 5000 variants, and k-mers (k=6) using Python, NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, and TensorFlow. Ideal for bioinformatics and machine learning research, it provides a foundation for studying variant effects in non-coding DNA regions.
Prerequisites

Python: Version 3.8 or higher recommended.
Jupyter Notebook: For running the notebook locally, or use Google Colab.
Dependencies: Listed in requirements.txt.

Installation

Clone the repository:git clone https://github.com/your-username/non_coding_variant_prediction.git
cd non_coding_variant_prediction


Set up a virtual environment (recommended):python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


Install dependencies:pip install -r requirements.txt


Open the notebook:jupyter notebook AI_Powered_Prediction_of_Non_Coding_Variant_Effects.ipynb

Alternatively, upload the notebook to Google Colab.

Usage

Run the notebook cells sequentially.
The notebook generates a 1M base pair genome and 5000 variants, which may require significant memory (at least 4GB RAM recommended).
The code processes variants into k-mers (k=6) for potential machine learning tasks.

Files

AI_Powered_Prediction_of_Non_Coding_Variant_Effects.ipynb: Main Jupyter notebook with the variant effect prediction pipeline.
requirements.txt: Python dependencies required to run the notebook.
.gitignore: Excludes unnecessary files (e.g., virtual environments, temporary files).
README.md: This file, providing project overview and instructions.

Troubleshooting

Dependency Conflicts: The notebook uses numpy==1.23.5 and tensorflow==2.10.0 for compatibility. If issues arise, try numpy>=1.26.0 and tensorflow==2.18.0, then test the notebook.
To check dependency compatibility:pip check


If issues persist, try:pip install tensorflow==2.10.0 numpy==1.23.5



Memory Issues: Generating a 1M base pair genome and 5000 variants can be memory-intensive. Ensure your system has sufficient resources or reduce the genome size in the notebook (e.g., change 1_000_000 to 100_000 in the code).
Notebook Rendering: View the notebook on GitHub or use nbviewer for a static render by pasting the notebook’s GitHub URL.



Contact
For questions, open an issue on this repository or contact [madavsankar08@gmail.com].
