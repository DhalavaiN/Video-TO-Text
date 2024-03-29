# Project Description: Automated Video Analysis

In this project, we aim to automate the analysis of video content using computer vision and natural language processing techniques. The primary goal is to identify specific objects or entities within the video frames and subsequently generate descriptive captions for each frame.

## Key Features

### 1. Video Download and Conversion
   - Utilize the `pytube` library to download a YouTube video.
   - Convert the video into individual frames using the `moviepy` library.

### 2. Image Classification
   - Employ a computer vision model to classify each frame based on predefined prompts (e.g., "person," "something else").
   - Classification using the Roboflow API for image similarity.

### 3. Video Captioning
   - Leverage the Hugging Face Transformers library to use a pre-trained model for image-to-text conversion.
   - Apply the model to generate descriptive captions for each frame.

### 4. Results Analysis
   - Analyze the results to determine:
     - Whether the specified entity (e.g., "person") is present in the video.
     - The timestamp when the entity first appears and the duration it remains visible.

### 5. Output and Visualization
   - Store the classification and captioning results in organized folders.
   - Optionally, create zip archives for easy download and distribution.

## Dependencies
   - The project relies on several Python libraries, including `opencv`, `pytube`, `imageio`, `moviepy`, `transformers`, and others.
   - Dependencies are managed using `pip install` commands.

## Workflow Automation
   - The project incorporates automation scripts for downloading, processing, and analyzing videos.
   - The automation ensures seamless execution of the entire workflow.




https://github.com/DhalavaiN/Video-TO-Text/assets/114598386/4cc35c25-9d15-4016-bd4c-c3f64d2c2f0d

