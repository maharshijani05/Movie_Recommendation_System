# Movie Recommender System

A simple movie recommendation system built with Python and Streamlit. This project uses machine learning techniques to provide personalized movie suggestions based on user preferences. It recommends 5 movies based on the selected movie.

## Features
- Recommends movies based on genre, cast, director, and user input.
- Interactive Streamlit interface.
- Content-based recommendation system.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-recommender-system.git
   cd movie-recommender-system
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
2. Select a movie from the dropdown to get recommendations.

## Dependencies
- Python 3.x
- Streamlit
- Pandas
- Scikit-learn
- Numpy

## Project Structure
```
movie-recommender-system/
│-- app.py               # Main application file
│-- movies.csv           # Dataset of movies
│-- requirements.txt     # Required dependencies
│-- README.md            # Project documentation
```

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

---
**Author:** Maharshi Jani
