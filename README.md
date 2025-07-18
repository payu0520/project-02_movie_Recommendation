# 🎬 project-02 Movie Recommendation System

This is a Content-Based Movie Recommendation System built using Python. It uses a similarity matrix and metadata from movies to suggest similar movies based on user input.

---

## 📁 Files in the Repository

| File | Description |
|------|-------------|
| `01-Data_Preprocessing.ipynb` | Data cleaning and preprocessing |
| `02-Recommendation.ipynb`     | Movie recommendation logic |
| `movies.csv`                  | Movie metadata |
| `cleaned_data.csv`            | Cleaned dataset |
| `movies.pkl`                  | Pickled movie data used in the recommendation |
| `upload_git_lfs.zip`          | Script to upload large files using Git LFS |

---

## ⚠️ Missing Files (Due to GitHub Size Limits)

GitHub restricts uploading files over 25MB. The following files could not be uploaded directly:

- `similarity.pkl` (used for recommendations)
- `credits.csv` (original movie metadata)

✅ You can upload them using the provided script.

---

## 📥 Upload Large Files with Git LFS

To upload `similarity.pkl` and `credits.csv` using Git LFS:

1. Download this zip: [upload_git_lfs.zip](upload_git_lfs.zip)
2. Extract it on your local machine.
3. Double-click on `upload_git_lfs.bat`.

> ℹ️ Make sure Git and Git LFS are installed on your system.

---

## 🚀 How It Works

1. User inputs a movie name.
2. Model computes similarity from the similarity matrix.
3. Returns top 5 similar movie recommendations.

---

## 💡 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Pickle
- Jupyter Notebooks
- Git & GitHub
- Git LFS (for large files)

---

## 📌 How to Run

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
jupyter notebook

👨‍💻 Author
payal Tanaji Chougale
email:payaltchougale1911@gmail.com



