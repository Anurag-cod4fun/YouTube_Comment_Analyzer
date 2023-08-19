# YouTube Comment Analysis

![YouTube Comment Analysis](comment_analysis.jpg)

This repository provides a simple tool for scraping comments from YouTube videos and performing sentiment analysis to classify the comments as positive or negative. The goal of this project is to gain insights into the sentiment of the viewers regarding a particular video.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Requirements](#requirements)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Introduction

YouTube is a platform where users can express their opinions and thoughts about videos through comments. Analyzing these comments can provide valuable insights into the sentiments and reactions of viewers towards a specific video. This project aims to automate the process of collecting comments and determining whether they are positive or negative in sentiment.

## Installation

1. Clone this repository to your local machine using:
   ```
   git clone https://github.com/your-username/youtube-comment-analysis.git
   ```

2. Navigate to the project directory:
   ```
   cd youtube-comment-analysis
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Obtain a YouTube API Key by following the instructions [here](https://developers.google.com/youtube/registering_an_application).

2. Replace `YOUR_API_KEY` in the `config.py` file with your obtained API key.

3. Run the script:
   ```
   python analyze_comments.py --video_url <YouTube Video URL>
   ```

4. The script will scrape the comments from the provided video URL and perform sentiment analysis on each comment.

## Requirements

- Python 3.x
- YouTube API Key
- Required Python packages (see `requirements.txt`)

## How It Works

1. The script uses the YouTube Data API to fetch the comments for the specified video.
2. It preprocesses the comments, removing any special characters and unnecessary elements.
3. Sentiment analysis is performed on each comment using a pre-trained sentiment analysis model.
4. Comments are classified as positive or negative based on the sentiment analysis score.
5. Results are displayed in the console, showing the percentage of positive and negative comments.

## Contributing

Contributions are welcome! If you find any issues or want to enhance the functionality, feel free to submit a pull request. Please ensure that your code follows the project's coding conventions.

---

**Disclaimer:** This project is for educational and non-commercial purposes only. The accuracy of sentiment analysis may vary, and the project authors are not responsible for any misuse or consequences of the analysis results. Use at your own discretion.

