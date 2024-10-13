
# YouTube Data Collection and Analysis Project

## Description
This project focuses on analyzing YouTube trending videos using the YouTube Data API. It allows you to extract detailed information about trending videos, such as video details, content statistics, and more, using Python. The project is designed to help understand YouTube trends and gather insights from the available data.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
  - [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)


## Features
- Fetches trending videos data from YouTube using the YouTube Data API.
- Extracts detailed information such as video statistics, content details, and metadata.
- Uses pandas for data manipulation and organization.
- Easy to modify for analyzing different regions or categories on YouTube.

## Installation

To run this project locally, ensure you have the following prerequisites:

- Python 3.7 or higher
- Jupyter Notebook
- Google API client library for Python

### Setup Instructions:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/youtube-analysis-project.git
   cd youtube-analysis-project
   ```

2. Install the required libraries:
   ```bash
   pip install pandas google-api-python-client
   ```

3. Replace the placeholder in the Jupyter notebook with your own API key:
   ```python
   API_KEY = 'YOUR_API_KEY_HERE'
   ```

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook youtube_analysis_project.ipynb
   ```

2. Run the notebook cells step by step to fetch and analyze the trending video data.

3. Modify the `get_trending_videos` function to change parameters like `max_results` for customized data retrieval.

## Project Structure

```
youtube-analysis-project/
│
├── youtube_analysis_project.ipynb  # Jupyter notebook with code and analysis
├── README.md                       # Project documentation
└── requirements.txt                # List of required libraries (optional)
```

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any improvements or suggestions.


