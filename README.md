# MGS3001-Python-for-Business
Course work for MGS 3001 Python Programming for Business
# MGS3001 Assignment 3
Student Name: Hanfei Xia

## Project Overview
This project analyzes the relationship between music’s AIGC rate and user evaluations (usefulness and novelty). The goal is to explore whether listeners perceive AI-generated music differently from human-created music, in terms of both its practical value and creative originality.

## Data Sources
- **Music AIGC Rate Data**: Includes audio and lyric AIGC rates, combined into a `Total_AI_Permeability` score. The score measures how “AI-like” a song sounds based on its composition and lyrics.
- **User Evaluation Data**: Usefulness and novelty scores for each song (outliers with a Novelty score of 1.0 were removed during cleaning to improve data quality).

## Dataset
The final dataset `FINAL_ANALYSIS_DATA.csv` contains 575 valid entries with these core columns:
- `artist_name`
- `song_name`
- `Total_AI_Permeability`
- `Usefulness`
- `Novelty`

## Code Structure
All analysis code is available in the `code/` folder, organized by workflow:
1.  `1.download_music.ipynb`: Collects song data from NetEase Cloud Music
2.  `2.Lyric_download.ipynb`: Downloads and cleans lyrics for each song
3.  `3.Novelty.ipynb`: Processes novelty evaluation scores
4.  `4.Usefulness.ipynb`: Processes usefulness evaluation scores
5.  `5.AIGC rate.ipynb`: Calculates audio and lyric AIGC rates
6.  `6.data_cleaning.ipynb`: Cleans and merges all datasets into the final file

## How to Run
1.  Install required packages:
    ```bash
    pip install pandas numpy scikit-learn librosa
Update README for Assignment 3
