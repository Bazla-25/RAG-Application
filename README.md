# NewsRAG - Intelligent News Retrieval and Analysis System

## Overview
NewsRAG is a Flask-based web application that leverages Retrieval-Augmented Generation (RAG) technology to fetch, analyze, and process news articles intelligently. The system allows users to search for news articles by topic and title, providing an enhanced way to interact with news content.

## Features
- Topic-based news article retrieval
- Title-specific search functionality
- Web-based user interface
- Article content scraping capabilities
- Intelligent content processing using RAG architecture

## Technology Stack
- Python
- Flask (Web Framework)
- Langchain (for RAG implementation)
- HTML/CSS (Frontend)

## Project Structure
```
NewsRAG/
├── app.py                    # Main Flask application
├── Langchain-agent(main).py  # RAG implementation
├── requirements.txt          # Project dependencies
├── scrap_article_content    # Article scraping module
├── statistic/               # Static assets
│   └── css/
│       └── style.css        # Custom styling
└── templates/               # HTML templates
    └── index.html          # Main application interface
```

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Bazla-25/RAG-Application.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python app.py
   ```

4. Access the application at `http://localhost:5000`

## Usage
1. Navigate to the web interface
2. Enter a topic of interest
3. Specify article title (optional)
4. Submit the search query
5. View and interact with the retrieved content

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
[MIT License](LICENSE)

## Author
- [Bazla-25](https://github.com/Bazla-25)

## Acknowledgments
- Thanks to all contributors and users of this project
- Built with Flask and Langchain