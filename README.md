#  YouTube Video Summarization using BART

## Overview
This project summarizes YouTube videos using Hugging Face's BART model. It extracts the transcript, checks the token length, applies chunking for long videos, and generates a concise summary.

## Technologies
- Python
- Hugging Face Transformers
- youtube-transcript-api
- NLTK

## Model
- facebook/bart-large-cnn

## Workflow
1. Extract the YouTube transcript.
2. Count the input tokens.
3. Generate the summary using BART.

## Result
The project successfully generates concise summaries while preserving the main ideas of the original video.
