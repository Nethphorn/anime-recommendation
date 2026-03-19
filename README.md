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

- `data/`: Contains the datasets used.
- `data-exploration.ipynb`: Initial notebook for cleaning and understanding the data.
- `preprocessing.ipynb`: Data cleaning and creation of the Content-Based Engine.
- `deep_learning_preprocessing.ipynb`: Preprocessing large user interaction data for neural networks (Phase 2).
- `requirements.txt`: List of Python libraries needed.
- `.gitignore`: Files and folders to be excluded from version control.

## Dataset
The dataset used in this project is the **[MyAnimeList Dataset](https://www.kaggle.com/datasets/azathoth42/myanimelist)** by azathoth42 on Kaggle. It includes:
- `AnimeList.csv`: Core information about ~14,000+ anime.
- `UserList.csv`: User demographic data.
- `UserAnimeList.csv`: Millions of individual user ratings.

Currently, the project is focusing on `AnimeList.csv` for content-based recommendations.

## Tech Stack
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

### Phase 1: Content-Based Engine (Completed ✅)
- [x] Initial Data Exploration
- [x] Data Cleaning & Preprocessing
- [x] Genre-based Similarity Matrix
- [x] Smart Recommendation Function (Weighted by Score)

### Phase 2: Deep Learning Collaborative Filtering (In Progress 🏗️)
- [/] Preprocessing User Interaction Data (`UserAnimeList.csv`)
- [ ] User & Anime Embedding Layers
- [ ] Neural Collaborative Filtering (NCF) Model Architecture
- [ ] Model Training & Evaluation (PyTorch)
- [ ] Hybrid Integration (Merging Content + Deep Learning)
