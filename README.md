🎬 Movie Recommendation System

A simple and interactive web application that recommends movies based on cast and crew information. Built with Python, Streamlit, and scikit-learn, it uses TF-IDF vectorization and cosine similarity to find movies similar to a user-input title.


---

Features

User-friendly interface using Streamlit.

Accepts any movie title present in the dataset.

Recommends the top 500 movies with similar cast and crew.

Fast and efficient search using TF-IDF vectorization.

Provides insight into movies that are contextually similar based on people involved in the production.



---

How It Works

1. Load Dataset: Reads a CSV/ZIP file containing movie information including title, cast, and crew.


2. Combine Text Data: Combines cast and crew into a single text field for analysis.


3. TF-IDF Vectorization: Converts textual data into numerical vectors using TF-IDF, ignoring common English stopwords.


4. Cosine Similarity: Computes similarity between movies based on their cast and crew vectors.


5. Recommendation Function: Returns the top 500 movies similar to the entered movie title.


6. Streamlit Interface: Provides a clean, interactive UI for users to enter a movie name and see recommendations instantly.




---

Installation

1. Clone the repository:



git clone <your-repo-url>

2. Install required packages:



pip install pandas scikit-learn streamlit

3. Place the dataset (movies1.csv or movies1.csv.zip) in the project folder.




---

Usage

1. Open a terminal in the project folder.


2. Run the Streamlit app:



python -m streamlit run movie_app.py

3. A browser window will open with the app interface.


4. Enter a movie title (exact title from the dataset) and click Recommend.


5. The app will display the top 500 similar movies based on cast and crew similarity.




---

Dataset

The project uses the TMDb 5000 Movie Dataset, which includes:

Movie titles

Cast details

Crew details



---

Example Movie Titles (from dataset)

The Dark Knight

Avatar

Inception

The Avengers

Jurassic Park


> Note: You must type the movie title exactly as it appears in the dataset to get recommendations.




---

Future Improvements

Include movie genres, keywords, and descriptions for more accurate recommendations.

Add poster images in the Streamlit app for a better visual experience.

Implement user rating-based filtering to refine recommendations.

Allow fuzzy search to accept partial movie titles instead of exact matches.



---

Technologies Used

Python 3.x

Pandas

scikit-learn (TF-IDF, cosine similarity)

Streamlit (web interface)



---

License

MIT License – free to use and modify.# dishap81-project1
