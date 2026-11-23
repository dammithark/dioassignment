# GOT-A Lab Evaluation – Practical Assessment & Capstone Case Study

**Program:** Government Officer Training – Advanced in Artificial Intelligence (GOT-A)  
**Institute:** NIELIT Delhi Centre – East Campus (Karkardooma), MeitY, Government of India  
**Participant:** [Your Full Name], [Designation], NIC [Division/State]

## Part A – Practical Laboratory Exercises
**Submission deadline:** 23 November 2026, 9:00 PM IST

| # | Exercise | Folder | Key outputs |
|---|----------|--------|-------------|
| 1 | Exploratory Data Analysis & Automated Reporting with Pandas | [Exercise1](Exercise1/) | Notebook, scatter plot, Excel file |
| 2 | Computer Vision – Image Blending using OpenCV | [Exercise2](Exercise2/) | Notebook, input & blended images |
| 3 | Generative AI – Prompt Engineering for Video Synthesis | [Exercise3](Exercise3/) | Notebook with prompt documentation |
| 4 | E-Commerce Text & Quantitative Analytics | [Exercise4](Exercise4/) | Notebook, product summary, word cloud |
| 5 | Interactive AI Prototyping with Gradio | [Exercise5](Exercise5/) | Notebook, interface screenshot |

## Part B – Capstone Case Study
**Submission deadline:** 24 November 2026, 9:00 PM IST

| Case Study | Folder | Key outputs |
|------------|--------|-------------|
| "Jan-Samadhan" – Smart Citizen Grievance Redressal & Policy Assistant | [Capstone](Capstone/) | Notebook, synthetic dataset, plots, confusion matrix |

The capstone is a proof-of-concept pipeline: PII masking → text cleaning → ML complaint routing → LLM triage and draft acknowledgment → RAG answers from an SOP → output validation → officer approval.

## Environment
- Python [version], Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, openpyxl, opencv-python, wordcloud, gradio, scikit-learn, google-genai

## How to run
1. Install dependencies:  
   `pip install pandas numpy matplotlib seaborn openpyxl opencv-python wordcloud gradio scikit-learn google-genai`
2. Open the notebook in each folder and run all cells (Kernel → Restart & Run All).
3. Exercise 4 needs the Kaggle dataset (see [Exercise4/README.md](Exercise4/README.md)); it is not included in this repository.
4. The capstone LLM steps need a Gemini API key, entered through a hidden prompt at runtime. No key is stored in this repository. Without a key, the notebook runs in offline mode and prints the prompts.
