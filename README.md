# Netflix Data Anaysis-with-EDA
<h2>🔍 Overview </h2>

Performed exploratory data analysis (EDA) on Netflix dataset to study content distribution, genres, and country-wise patterns.

<h2> steps for the project </h2>

data explore

data cleaning 

descriptive statistics
 
data visualization

<h2>🛠️ Tech Stack </h2>

Python (Pandas, NumPy, Seaborn, Matplotlib)

## 📂 Dataset Preview
Dataset Preview
<img width="1298" height="274" alt="image" src="https://github.com/user-attachments/assets/d51e9cc1-1854-4889-9108-a98a0ca4b559" />





📊 Key Insights

Top genres: Drama, Comedy.

Content growth: Rapid increase after 2015.

Country-wise distribution: US dominates, India emerging.


<h3>top 15 genre </h3>

<img width="1266" height="638" alt="image" src="https://github.com/user-attachments/assets/92ab8e15-7e12-48c7-8f5b-ab94063efcaa" />

<h3>content distribution by country</h3>

<img width="1532" height="577" alt="image" src="https://github.com/user-attachments/assets/46839cb5-38f5-480b-b825-da5e746da141" />


<h3>trends in Genre popularity over time </h3>

<img width="1546" height="574" alt="image" src="https://github.com/user-attachments/assets/38b3e7af-35a5-4795-9af2-6dda21ce5ec8" />


<h3>language estimation </h3>

<img width="1551" height="586" alt="image" src="https://github.com/user-attachments/assets/17db3bbc-4f8d-4bf7-8439-e52576f3e80f" />

<h3>Conclusions:</h3>

Data Cleaning: Missing values were handled — “Unknown” was used for `director`, `cast`, and `country`; mode was used for `date_added` and `duration`.

Duration Split: `duration` was split into `duration_num` (numeric) and `duration_type` (either "min" or "season").

Movie Durations: Fairly symmetric distribution with significant variation; average around 90–120 minutes.

TV Show Durations: Mostly 1-season shows dominate the catalog; limited long-running series.

Genre Column: `listed_in` was renamed to `Genre` for better clarity.





