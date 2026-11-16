BE AIDS – CL-II PRACTICALS

Folders:
- Quantum_AI: 5 practicals as plain .txt files.
- Information_Retrieval: 5 practicals as plain .txt files.
- Information_Retrieval/datasets: all included sample data files.
- requirements.txt: Python packages used across practicals.
- DATASET_NOTES.txt: provenance and limitations of bundled sample datasets.

FORMAT:
Each Practical_N.txt is a copy/paste-ready practical handout. Code blocks are
separated by a single hyphen (-) on its own line, as requested. Copy and run
each code block in order in Jupyter or a Python environment. Do NOT paste the
separator hyphen lines into a Python cell.

SETUP:
1. Extract the ZIP.
2. Open a terminal in the extracted BE_AIDS_CL_II folder.
3. Install packages: python -m pip install -r requirements.txt
4. Start Jupyter from this root folder so relative paths such as
   Information_Retrieval/datasets/... can be adjusted as noted in each practical.
5. For IR practicals that read datasets, run from inside the
   Information_Retrieval folder OR update the relative dataset path to
   datasets/<filename>.

IMPORTANT:
The included heart disease and spam datasets are labelled synthetic demo
samples, not official benchmark datasets. See DATASET_NOTES.txt. The
customer-clustering sample is also synthetic; the supplied college notebook
uses CC_GENERAL.csv. These distinctions are intentional so the ZIP is honest
and runs without pretending sample data are official datasets.

No IBM Quantum account or API key is needed for the QAI simulator exercises.
