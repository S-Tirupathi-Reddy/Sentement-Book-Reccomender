# Sentiment_Book_Recommender

Welcome to the Sentiment Book Recommender! This application helps users discover books tailored to their interests and current mood by leveraging advanced Natural Language Processing (NLP) techniques and sentiment analysis.

Overview
In today's vast literary world, finding the right book that matches both your interests and mood can be challenging. This recommender system addresses this by:

- Analyzing user queries to understand their preferences.
- Filtering books based on genre and desired emotional tone.
- Providing personalized book recommendations with relevant details and cover images.
## Features
- Natural Language Query Processing: Understands user input to fetch relevant book recommendations.
- Category Filtering: Allows users to filter books by genres such as Fiction, Non-Fiction, etc.
- Sentiment Filtering: Matches books to the user's current mood, including sentiments like Happy, Surprising, Sad, Angry, and Fearful.
- Interactive User Interface: A user-friendly interface built with Gradio for seamless interactions.
## Installation
To set up the Sentiment Book Recommender locally, follow these steps:

## Clone the Repository:
```bash
git clone https://github.com/anandreddy05/Sentiment-Book-Recommender.git
```
```bash
cd Sentiment-Book-Recommender
```
## Set Up a Virtual Environment:

It's recommended to use a virtual environment to manage dependencies.
```bash
python3 -m venv venv
```
```bash
use venv\Scripts\activate
```
## Install Dependencies:

Ensure you have Python 3.7 or later installed. Then, install the required packages:
```bash
pip install -r requirements.txt
```
Download Necessary Resources:

Datasets: Place your book dataset (books_with_image_paths.csv) in the datasets directory.
Tagged Descriptions: Ensure tagged_desc.txt is available in the notebooks directory.
Set Up Environment Variables:

Create a .env file in the root directory and add any necessary environment variables. For example:

API_KEY=your_api_key_here
Usage
To run the application:
- python app.py
This will launch the Gradio interface. Open the provided local URL in your browser to interact with the recommender system.

Using the Application:

Enter a Query: Describe the type of book you're looking for. For example, "A thrilling mystery set in Victorian London."
Select a Category: Choose a genre from the dropdown menu.
Select a Mood/Sentiment: Pick the mood you're in or the emotional tone you'd like the book to have.
Find Books: Click on the "Find Books" button to receive personalized recommendations.

datasets/: Contains the book dataset.
notebooks/: Includes text data and any Jupyter notebooks.
scraping/: Scripts or data related to web scraping (if applicable).
app.py: Main application script.
requirements.txt: List of Python dependencies.
.env.example: Example environment variables file.
## Technologies Used
- Python: Core programming language.
- Pandas & NumPy: Data manipulation and analysis.
- Regular Expressions (re): Text processing.
- Langchain: For document loading and text splitting.
- Hugging Face Transformers: For embeddings and sentiment analysis.
- FAISS: Efficient similarity search and clustering.
- Gradio: Building the interactive user interface.
## Contributing
Contributions are welcome! If you'd like to improve this project, please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
