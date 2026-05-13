# Data Description
## 1. Basic Dataset Information
- Dataset Name: FINAL_ANALYSIS_DATA.csv
- Number of Rows: 575
- Number of Columns: 5
- Data Collection Time: April 2025
- Data Source: NetEase Cloud Music

## 2. Data Collection Method
Data was collected using Python web scraping and API access from NetEase Cloud Music platform. We collected song information, artist names, and AI-related evaluation scores.

## 3. Variable Description
| Variable Name | Type | Description | Example |
|--------------|------|-------------|---------|
| artist_name | String | Name of the singer/artist | Jay Chou |
| song_name | String | Title of the song | Qi Li Xiang |
| Total_AI_Permeability | Float | Overall AI generation score | 0.72 |
| Usefulness | Float | User-rated usefulness score | 4.5 |
| Novelty | Float | User-rated novelty score | 3.9 |

## 4. Data Quality
- No missing values
- Removed outliers (Novelty = 1.0)
- All data cleaned and standardized
- Final dataset ready for analysis
