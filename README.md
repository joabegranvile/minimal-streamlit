# Minimal Streamlit Book App

A simple web application built with Streamlit for browsing and reviewing trending books. This app allows users to explore the top 100 trending books, filter them by price, and view detailed information and customer reviews for individual books.

## Features

- **Home Page**: View and filter the top 100 trending books by price range. Includes visualizations of publication years and price distributions.
- **Books Reviews Page**: Select a specific book to view its details (title, genre, price, rating, year) and read customer reviews presented as chat messages.
- **Interactive Sidebar**: Filter books by price on the home page and select books for detailed views.
- **Data Visualizations**: Bar charts and histograms using Plotly for data insights.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/joabegranvile/minimal-streamlit.git
   cd minimal-streamlit
   ```

2. Install the required dependencies:
   ```
   pip install streamlit pandas plotly
   ```

## Usage

1. Run the Streamlit app:
   ```
   streamlit run lista.py
   ```

2. Open your web browser and navigate to the provided local URL (usually `http://localhost:8501`).

3. Use the sidebar on the home page to adjust the price range and explore books.

4. Navigate to the "Books Reviews" page to select a book and view its details and reviews.

## Datasets

The app uses two CSV datasets located in the `datasets/` directory:

- `Top-100 Trending Books.csv`: Contains information about the top 100 trending books, including title, genre, price, rating, and year of publication.
- `customer-reviews.csv`: Contains customer reviews for the books, including reviewer name, review text, and associated book name.

## Requirements

- Python 3.7+
- Streamlit
- Pandas
- Plotly

## Project Structure

```
minimal-streamlit/
├── datasets/
│   ├── customer-reviews.csv
│   └── Top-100 Trending Books.csv
├── pages/
│   └── books_reviews.py
├── lista.py
└── README.md
```

- `lista.py`: Main home page script.
- `pages/books_reviews.py`: Books reviews page script.
- `datasets/`: Directory containing the CSV data files.

## Contributing

Feel free to fork the repository and submit pull requests for improvements or additional features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
