# IMDB Movie Analysis with Python & pandas

A simple yet insightful data analysis project using Python and pandas to explore and visualize trends in a movie dataset.  
Analyzed IMDB-style data to discover top-rated movies by genre, rating trends over the years, and genre popularity patterns.

---

## 📌 Project Goals

- 📊 Identify **top-rated movies** per genre.
- 📅 Visualize **average rating trends** over the years.
- 🎭 Analyze how **genre popularity** changes over time.

---

## 🗂️ Dataset

You can use any dataset that contains movie metadata, such as:

- `title`: Movie name
- `genre`: Comma-separated list of genres (e.g., `"Action,Drama"`)
- `rating`: IMDB-style rating (e.g., `8.7`)
- `year`: Year of release


📁 **File used:** IMDB_Movie-Data.csv (Dataset sourced from Kaggle – IMDB Data)

> **Note**: If your dataset has different column names, you’ll need to rename them accordingly in the notebook.

---

## ⚙️ Technologies Used

| Tool          | Purpose                          |
|---------------|----------------------------------|
| `Python 3.x`  | Main programming language        |
| `pandas`      | Data cleaning and manipulation   |
| `matplotlib`  | Plotting and data visualization  |
| `seaborn`     | Enhanced visualization styling   |
| `Jupyter`     | Interactive notebook environment |

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/imdb-movie-analysis.git
cd imdb-movie-analysis
```

### 2️⃣ Install Required Libraries

Use pip to install dependencies:

```bash
pip install pandas matplotlib seaborn
```

Or with `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Jupyter Notebook

```bash
jupyter notebook dataset.ipynb
```

---

## 📊 Visual Insights

### 🎥 Top 5 Movies per Genre

```
Genre: Drama
1. The Shawshank Redemption (9.3)
2. Forrest Gump (8.8)
...

Genre: Action
1. The Dark Knight (9.0)
2. Inception (8.8)
...
```

---

### 🕒 Average Rating Over the Years

A line plot showing how movie ratings change over time, indicating historical trends and audience preferences.

---

### 🎭 Genre Popularity Over Time

A multi-line chart visualizing how frequently each genre appears in movies across different years.

---

## 📁 Project Structure

```
.
├── dataset.ipynb          # Main Jupyter Notebook with analysis
├── imdb_movies.csv        # Input movie dataset (CSV format)
├── README.md              # This file
└── requirements.txt       # (Optional) List of required Python packages
```

---

## 📌 To-Do / Future Improvements

- [ ] Add interactive visualizations with Plotly or Streamlit  
- [ ] Integrate movie revenue analysis  
- [ ] Build a dashboard or report export (PDF/Excel)  

---

## 🙋‍♂️ Author

**aranyaadheu**  
📫 [Portfolio](https://aranyaadheu.vercel.app/) • 🌐 [GitHub](https://github.com/aranyaadheu)

If you like this project, consider giving it a ⭐ on GitHub!

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 📎 Acknowledgements

- Dataset inspired by [IMDB](https://www.imdb.com/) and [Kaggle](https://www.kaggle.com/)
- Built using open-source libraries like `pandas`, `matplotlib`, and `seaborn`

---

## ✅ Optional: `requirements.txt`

```
pandas
matplotlib
seaborn
```
