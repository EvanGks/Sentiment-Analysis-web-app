# 🌍 Multilingual Sentiment Analysis Web App

This project demonstrates advanced AI integration, modern web development, and best practices for deploying intelligent applications. It analyzes sentiment in text across dozens of languages using the Hugging Face Inference API and the [tabularisai/multilingual-sentiment-analysis](https://huggingface.co/tabularisai/multilingual-sentiment-analysis) model, with automatic language detection and a beautiful, responsive user interface.

---

## 🚀 Why This Project?

- **Portfolio-Ready:** Designed to highlight your expertise in AI, API integration, and full-stack development.
- **Remote Inference:** Uses Hugging Face's hosted API—no heavy local models required.
- **Multilingual:** Supports sentiment analysis in 20+ languages, making it globally accessible.
- **Modern UI:** Responsive, visually dynamic interface that adapts to sentiment results.
- **Robust Engineering:** Includes error handling, environment variable management, and a comprehensive test suite.

---

## ✨ Features

- Multilingual sentiment analysis (Very Positive, Positive, Neutral, Negative, Very Negative)
- Real-time results with color-coded, animated feedback
- Automatic language detection for user input
- Responsive, mobile-friendly design
- Seamless integration with Hugging Face Inference API
- Clear error messages and user guidance
- Easily extensible and well-documented codebase

## Supported Languages

This application supports sentiment analysis in the following languages:
- English
- Spanish
- French
- German
- Italian
- Portuguese
- Dutch
- Polish
- Russian
- Czech
- Arabic
- Chinese
- Korean
- Japanese
- Hindi
- Bengali
- Turkish
- Indonesian
- And many more (see the [model card](https://huggingface.co/tabularisai/multilingual-sentiment-analysis) for details)

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask (Python)
- **ML Model API**: [Hugging Face Inference API](https://huggingface.co/inference-api) with [tabularisai/multilingual-sentiment-analysis](https://huggingface.co/tabularisai/multilingual-sentiment-analysis)
- **Language Detection**: langdetect

## Installation

1. Clone this repository:
```
git clone https://github.com/EvanGKS/multilingual-sentiment-analysis-app.git
cd multilingual-sentiment-analysis-app
```

2. Create a virtual environment and activate it:
```
python -m venv venv
# On Windows
.\venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

3. Install dependencies:
```
pip install -r requirements.txt
```

4. Create a `.env` file in the root directory (copy from `.env.example`):
```
cp .env.example .env
```

5. Get a Hugging Face API token from [https://huggingface.co/settings/tokens](https://huggingface.co/settings/tokens) and add it to your `.env` file:
```
HUGGINGFACE_API_KEY=your_api_key_here
```

Note: The application will work with limited functionality without an API key, but it's recommended to set one up for production use.

## Running the Application

1. Start the Flask server:
```
python app.py
```

2. Open your browser and go to:
```
http://localhost:5000
```

## Running Tests

Run tests using pytest:
```
pytest
```

## Project Structure

```
.
├── app.py                  # Main Flask application
├── requirements.txt        # Python dependencies
├── .gitignore              # Git ignore file
├── .env.example            # Example environment variables
├── .env                    # Environment variables (create this, not tracked in git)
├── README.md               # Project documentation
├── static/                 # Static assets
│   ├── css/                # CSS stylesheets
│   │   └── style.css       # Main stylesheet
│   └── js/                 # JavaScript files
│       └── script.js       # Main JavaScript file
├── templates/              # HTML templates
│   └── index.html          # Main page template
└── tests/                  # Test directory
    ├── __init__.py         # Makes tests a package
    ├── test_app.py         # Tests for Flask app
    └── test_sentiment.py   # Tests for sentiment analysis
```

## License

This project is licensed under the [MIT License](./LICENSE) © 2025 Evan GKS.

## Author

Evan GKS

For questions or feedback, please reach out via:
- **GitHub:** [EvanGks](https://github.com/EvanGks)
- **X (Twitter):** [@Evan6471133782](https://x.com/Evan6471133782)
- **LinkedIn:** [Evangelos Gakias](https://www.linkedin.com/in/evangelos-gakias-346a9072)
- **Kaggle:** [evangelosgakias](https://www.kaggle.com/evangelosgakias)
- **Email:** [evangks88@gmail.com](mailto:evangks88@gmail.com)

---

Happy coding!!
