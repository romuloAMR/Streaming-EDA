# Streaming Services Exploratory Data Analysis (EDA-Streaming)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Poetry](https://img.shields.io/badge/Poetry-Dependency%20Manager-blue)

This project performs an exploratory data analysis (EDA) of major streaming services: Netflix, Amazon Prime Video, Disney+, and Hulu.

## 📊 About the Project

EDA-Streaming is a data analysis project that investigates and compares the content catalogs available on major streaming platforms. The goal is to extract insights about patterns, trends, and characteristics of the content offered by each service.

### Services Analyzed
- **Netflix**
- **Amazon Prime Video** 
- **Disney+**
- **Hulu**

## 🗂️ Data Sources

Data was obtained from Kaggle through the following datasets:

| Service | Data Source (Kaggle) |
| :--- | :--- |
| Netflix | [Netflix Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) |
| Prime Video | [Amazon Prime Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows) |
| Disney+ | [Disney Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/disney-movies-and-tv-shows) |
| Hulu | [Hulu Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/hulu-movies-and-tv-shows) |

## 🛠️ Technologies Used

- **Python 3.10**
- **Jupyter Notebook** - For interactive analysis and visualization
- **Pandas** - Data manipulation and analysis
- **DevContainer** - Containerized development environment
- **Poetry** - Dependency management and virtual environment

## 🚀 How to Run the Project

### Prerequisites
- Docker
- VS Code with Dev Containers extension
- Git

### Environment Setup

1. **Clone the repository:**
   ```bash
   git clone [[repository-url]](https://github.com/romuloAMR/Streaming-EDA.git)
   cd EDA-Streaming
2. **Open in VS Code:**

   ```bash
   code .
   ```

3. **Open in DevContainer:**

- Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac)

- Select "Dev Containers: Reopen in Container"

- Wait for the container to build

4. **Run Notebooks**
- First run `download_and_join.ipynb`
- So run `eda.ipynb`

# 📊 Dataset Attributes

`type`: Content type (Movie or TV Show)  
`title`: Title of the movie or TV show  
`director`: Director name  
`cast`: Main cast members  
`country`: Production country  
`date_added`: Date added to streaming platform  
`release_year`: Original release year  
`rating`: Age rating (PG, TV-MA, R, etc.)  
`duration`: Duration (minutes for movies, seasons for TV shows)  
`listed_in`: Genres and categories  
`description`: Content description/synopsis  
`streaming`: Streaming platform (Netflix, Prime, Disney+, Hulu)

### Authors
- [Rômulo Alves de Morais Rocha](https://github.com/romuloAMR)
- [Sávio Emanuel Mariano Fonseca](https://github.com/savioemanuelf)
