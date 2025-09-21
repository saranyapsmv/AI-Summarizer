# Youtube Summariser

[![Youtube Summary App]"https://github.com/saranyapsmv/AI-Summarizer.git"]

## Why YouTube Summariser

For many videos, the main content of the videos is only 50-60% of the total length.</ul>

Youtube summarizer will summarize the content of the video by keeping all the important points and making it short and easily understandable.</ul>

Summarizing transcripts of such videos automatically allows us to quickly look out for the important patterns in the video and helps us to save time and efforts to go through the whole content of the video.</ul>

## How it Works

![Youtube Summarizer]
https://github.com/saranyapsmv/AI-Summarizer.git

## App Features

1. **Video Transcript Extraction**: Automatically extracts transcripts from YouTube videos using the video URL.

2. **Multiple Summarization Techniques**: Supports different summarization algorithms including Gensim, NLTK, Spacy, and TF-IDF for extractive summarization, as well as T5-based abstractive summarization.

3. **Language Translation**: Translates summaries into various languages using the deep_translator library.

4. **Text-to-Speech**: Converts summaries into audio format, making the content more accessible
 
5. **Customizable Summary Length**: Allows users to select the desired summary length.

6. **Interactive UI**: Built with Streamlit, the application offers an easy-to-use interface for all functionalities.
   

## Installation

System: Python3.8

1. ```git clone https://github.com/saranyapsmv/AI-Summarizer.git```
2. ```cd Youtube-Summariser```
3. ```pip install -r requirements.txt```
4. ```pip install streamlit>=1.8.1```
5. ```streamlit run app.py```


## App Usage

1. **Enter YouTube Video URL**: Paste the URL of the YouTube video you want to summarize in the provided input field.

2. **Select Summarization Type**: Choose between extractive and abstractive summarization methods.

3. **Choose Summarization Algorithm**: If you select extractive summarization, pick one of the available algorithms (Gensim, NLTK, Spacy, or TF-IDF).

4. **Set Summary Length**: Use the slider to select the percentage length of the summary relative to the original transcript.

5. **Select Language for Translation**: Choose the language in which you want the summary to be translated.

6. **Generate Summary**: Click on the 'Summarize' button to process the video transcript and display the summary.

7. **Listen to Summary**: If desired, play the audio version of the summary.





	

