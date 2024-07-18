# YouTube Transcript to Detailed Notes Converter

## Overview

This project converts YouTube video transcripts into detailed summaries using Google Gemini AI. It extracts the transcript from a YouTube video, processes it with a generative model, and provides a concise summary in point form within 250 words. This tool is designed to help users quickly grasp the essential content of a video.

## Key Features

- **YouTube Transcript Extraction**: Retrieves the entire transcript of a YouTube video using the YouTube Transcript API.
- **Summarization with Google Gemini AI**: Utilizes the Google Gemini Pro generative model to summarize the extracted transcript.
- **User-Friendly Interface**: Built with Streamlit to provide an intuitive interface for users to input YouTube links and receive detailed notes.

## Methodology

1. **Load Environment Variables**: Uses `dotenv` to load API keys and other environment variables.
2. **YouTube Transcript Extraction**: Extracts transcript text from a given YouTube video URL using the YouTube Transcript API.
3. **Google Gemini AI Integration**: Configures and utilizes the Google Gemini Pro generative model to process and summarize the transcript text.
4. **Streamlit UI**: Provides a simple web interface for users to enter YouTube links, view video thumbnails, and generate detailed notes.

## Implementation

The project is implemented in Python with the following key components:

- **Streamlit**: For building the user interface.
- **dotenv**: For loading environment variables.
- **YouTube Transcript API**: For extracting video transcripts.
- **Google Gemini AI**: For generating content summaries.


## Future Work

- **Enhanced Summarization**: Improve summarization accuracy by fine-tuning the generative model.
- **Support for Multiple Languages**: Extend support for transcripts and summaries in various languages.
- **Extended Functionality**: Add features like keyword extraction and sentiment analysis.
- **User Authentication**: Implement user authentication to manage usage and API rate limits.

## Acknowledgments

Special thanks to the developers of Streamlit, YouTube Transcript API, and Google Gemini AI for providing the tools and libraries used in this project.

## Results

![image](https://github.com/user-attachments/assets/27e08a5d-1846-4180-8d77-a6b9527827c7)

![image](https://github.com/user-attachments/assets/d16bedef-8260-428e-9b6c-154d496dd9c4)

![image](https://github.com/user-attachments/assets/8ec8e64d-4107-4735-ac61-cd1866a7e23d)

![image](https://github.com/user-attachments/assets/9521aad2-d45e-44dd-971e-a2a474460ae2)



