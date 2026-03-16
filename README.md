# Anime Recommendation System

This project aims to build a recommendation engine for anime using machine learning. It explores user preferences, anime genres, and ratings to suggest the next best watch.

## Getting Started

### Prerequisites
- Python 3.x
- [pip](https://pip.pypa.io/en/stable/installation/)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/AnimeRecommendation.git
   cd AnimeRecommendation
   ```

2. **Set up a virtual environment:**
   ```bash
   python -m venv .venv
   ```

3. **Activate the environment:**
   - **Windows:**
     ```bash
     .venv\Scripts\activate
     ```
   - **Mac/Linux:**
     ```bash
     source .venv/bin/activate
     ```

4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Project Structure

- `data/`: Contains the datasets used (Note: ignored by git if large).
- `data-exploration.ipynb`: Initial notebook for cleaning and understanding the data.
- `requirements.txt`: List of Python libraries needed.
- `.gitignore`: Files and folders to be excluded from version control.

## Dataset
The dataset currently being explored is the **AnimeList** CSV, which includes features like:
- `anime_id`, `title`, `genre`, `score`, `popularity`, and `members`.

## Tech Stack
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Roadmap
- [x] Initial Data Exploration
- [ ] Data Cleaning & Preprocessing
- [ ] Exploratory Data Analysis (EDA)
- [ ] Feature Engineering
- [ ] Model Selection & Training
- [ ] Evaluation & Optimization
