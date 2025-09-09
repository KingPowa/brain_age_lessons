# Brain Age Prediction Lessons  
### Summer School on Artificial Intelligence in Health and Life Sciences  
Università Campus Bio-Medico di Roma  

This repository provides a gentle introduction to neuroimaging and guides you through the basics of brain age prediction.  
It also includes an explainability pipeline to better understand model decisions.  

The repository was used for the **lessons of the Summer School** held at **Università Campus Bio-Medico di Roma (UCBR)** on **10/09/2025**.  

---

## 📂 Data  

The dataset used in this course is available on Kaggle:  
👉 [Preprocessed IXI Dataset with FreeSurfer 8](https://www.kaggle.com/datasets/kingpowa/preprocessed-ixi-dataset-with-fs8/data)  

It is advised to download the dataset beforehand.  
The code for downloading and organizing the dataset is also provided in the **first lesson notebook**.  

---

## 📁 Repository Structure  

- **`notebooks/`** → Contains the lesson notebooks.  
  *These are not complete — exercises are included for you to work on.*  

- **`notebooks_complete/`** → Contains the same lessons with exercises solved and annotated with *possible* solutions.  
  *Tip: Try the notebooks in `notebooks/` first before checking the completed versions.*  

- **`results/`** → Training logs and traces of the models used in the lessons.  
  *Useful as a reference to compare against your own training runs.*  

- **`checkpoints/`** → Pre-trained checkpoints of the models.  
  *You can use these directly to analyze model performance without retraining.*  

- **`data/`** → Sample data used in the lessons, including small examples to explain various concepts.  
  *All data is open-source.*  

---

## ⚙️ Requirements  

Some libraries are required to run the lessons.  
Most dependencies can be installed directly from the notebooks, but a `requirements.txt` file is also provided.  

### Install Requirements  

```bash
# Clone the repository
git clone https://github.com/KingPowa/brain_age_lessons.git
cd <repository_folder>

# (Optional but recommended) Create a virtual environment
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install the requirements
pip install -r requirements.txt
```

If you are running the notebooks on Google Colab or Kaggle Notebooks, the installation commands are included at the beginning of each notebook.

---

## 🎓 Acknowledgments

These materials were prepared for the
Summer School on Artificial Intelligence in Health and Life Sciences
at Università Campus Bio-Medico di Roma (UCBR).

Instructor(s): Francesco Sammarco
Date: 10 September 2025