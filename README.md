# Reddit Comment Sentiment Analysis App: Link https://reddit-post-comments-sentimentanalysis.streamlit.app/

## Description
The Reddit Comment Sentiment Analysis App is a web application that allows users to scrape comments from a Reddit post, perform sentiment analysis on them, and provide data analytics in the form of bar graphs and pie charts. The app aims to provide insights into the sentiment distribution of comments and offer a filtered view of comments based on their sentiment.

## Architecture
The application is built using the following components:

- **Streamlit**: The web application framework used to create the user interface and handle user interactions. It provides an intuitive interface for users to input the Reddit post URL and view the sentiment analysis results and data analytics.

- **PRAW (Python Reddit API Wrapper)**: PRAW is used to interact with the Reddit API and scrape comments from the specified Reddit post. It handles authentication and retrieval of comments for analysis.

- **Sentiment Analysis**: The app utilizes a sentiment analysis model or library to analyze the sentiment of the comments. The specific sentiment analysis technique used can vary, such as using pre-trained models, rule-based approaches, or machine learning-based classifiers.

- **Data Analytics**: The app leverages data visualization libraries, such as Matplotlib, to generate bar graphs and pie charts based on the sentiment analysis results. These visualizations provide an overview of the sentiment distribution and allow users to gain insights into the data.

## Requirements
To run the Reddit Comment Sentiment Analysis App, the following requirements should be met:

- Python 3.x: The application is written in Python, so a compatible version of Python should be installed.

- Dependencies: Install the required Python libraries by running `pip install -r requirements.txt`. Ensure that the `requirements.txt` file contains all the necessary dependencies for the project, including Streamlit, PRAW, sentiment analysis libraries, and data visualization libraries.

- Reddit API credentials: To scrape comments from Reddit, you need to provide valid API credentials. Create a Reddit API application and obtain the client ID, client secret, and user agent, which will be used for authentication.

## Technologies Used
The Reddit Comment Sentiment Analysis App is built using the following technologies:

- Python: The primary programming language used for development.

- Streamlit: The web application framework used to create the user interface.

- PRAW: The Python Reddit API Wrapper library for interacting with the Reddit API.

- Sentiment analysis libraries: The specific sentiment analysis library or model used for analyzing the sentiment of the comments.

- Matplotlib: A data visualization library used for generating bar graphs and pie charts.

- Other Python libraries: Other libraries may be used for various tasks, such as data manipulation, data preprocessing, and data analysis.

## Getting Started
To get started with the Reddit Comment Sentiment Analysis App, follow these steps:

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/your-username/reddit-comment-sentiment-analysis.git
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up the Reddit API credentials by creating a `praw.ini` file or providing the necessary credentials through environment variables. Refer to the PRAW documentation for detailed instructions.

4. Run the application:
   ```
   streamlit run app.py
   ```

5. Access the application in your web browser at `http://localhost:8501` or the URL provided by Streamlit.

## Usage
1. Open the application in your web browser.

2. Enter the URL of the Reddit post you want to analyze.

3. Click the "Analyze" button to initiate the sentiment analysis and data analytics.

5. Explore the sentiment analysis results, which may include overall sentiment statistics, sentiment distribution, and a filtered view of comments based on sentiment.

6. Interact with the provided bar graphs and pie charts to gain insights into the sentiment distribution.

7. Experiment with different Reddit post URLs to analyze comments from various posts.

## Contributing
Contributions to the Reddit Comment Sentiment Analysis App are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request on the GitHub repository.

## License
This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize the README file according to your specific project details and preferences.
