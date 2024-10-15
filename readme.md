# Amazon Top 100 Best-Selling Books (November 2023) Web Application

This project is an interactive web application built using **Streamlit**, designed to display the top 100 best-selling books on Amazon from November 2023. It provides users with insights into book trends, pricing, and reviews, allowing them to explore the latest popular titles and filter them according to their preferences.

## Features

### 1. **Interactive Books Dashboard**
   - Displays a list of the top 100 trending books based on data fetched from a CSV file (`Top-100 Trending Books.csv`).
   - Users can filter books by price range using a **slider** in the sidebar.
   - Visualizations using **Plotly** include:
     - A bar chart showing the distribution of books by year of publication.
     - A histogram representing the distribution of book prices.
   - Responsive layout using Streamlit's column feature for side-by-side charts.

### 2. **Book Review Page**
   - Provides detailed information for each book, including:
     - Title
     - Genre
     - Price
     - Customer rating
     - Year of publication
   - Users can select a book from a dropdown list in the sidebar to view specific details.
   - Customer reviews are displayed in a chat-like format, showing reviewer names, titles, and comments.
   - Reviews are dynamically filtered based on the selected book.

## Data Sources
The application loads two CSV files:
- `Top-100 Trending Books.csv`: Contains data about the top 100 books, including their title, price, genre, rating, and year of publication.
- `customer reviews.csv`: Stores customer reviews for the listed books, including reviewer names, review titles, and detailed comments.

## Visualizations
- **Bar Chart**: Represents the number of books published each year from the list of best-sellers.
- **Histogram**: Displays the price distribution of the top 100 books, allowing users to quickly identify price trends.

## Technology Stack
- **Python**
- **Streamlit** for building the web application.
- **Pandas** for data manipulation.
- **Plotly Express** for interactive visualizations.

## How to Run the Project

1. Clone the repository to your local machine.
2. Install the necessary dependencies using the following command:
   ```bash
   pip install -r requirements.txt
   ```
3. Place the CSV files (`Top-100 Trending Books.csv` and `customer reviews.csv`) in the `datasets` folder.
4. Run the application with:
   ```bash
   streamlit run app.py
   ```
5. Open the provided URL in your browser to interact with the web application.

## Conclusion
This web app offers a simple and intuitive way for users to explore the most popular books on Amazon, with detailed insights into pricing, genres, ratings, and customer feedback. It is ideal for book enthusiasts looking to stay up-to-date with the latest trends in the literary world.

---

This README provides a structured overview of the project, the code functionality, and instructions for running the application.