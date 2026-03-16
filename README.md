# Spotify Streaming History Deep Dive

This repository contains a comprehensive analysis of personal Spotify streaming history data. Using Python and popular data analysis libraries, it explores listening patterns, top artists, tracks, and temporal trends from extended streaming history JSON files.

## Overview

The analysis includes:
- Total listening time and daily trends
- Top artists and tracks by listening duration
- Listening patterns by hour of day and day of week
- Per-artist catalog summaries
- Year-by-year listening summaries

## Data Source

The analysis uses Spotify's Extended Streaming History data, which includes:
- Audio streaming history files (multiple JSON files covering different time periods)
- Video streaming history (optional)
- Metadata like track names, artists, albums, timestamps, and play durations

## Prerequisites

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab for running the analysis notebook

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

   The main dependencies include:
   - pandas: For data manipulation and analysis
   - numpy: For numerical operations
   - matplotlib: For plotting
   - seaborn: For statistical data visualization

## Usage

1. Place your Spotify Extended Streaming History JSON files in the repository root directory.

2. Open the Jupyter notebook:
   ```bash
   jupyter notebook spotify_analysis.ipynb
   ```

3. Run the cells in order to:
   - Load and process the streaming history data
   - Generate visualizations and summaries
   - Explore your listening patterns

## Data Processing

The notebook performs the following key transformations:
- Converts timestamps to datetime objects
- Extracts date, year, month, day of week, and hour components
- Calculates listening time in minutes
- Cleans and standardizes track and artist names
- Aggregates data for various analyses

## Visualizations

The analysis includes several charts:
- Daily listening trends over time
- Top 20 artists by listening time
- Top 20 tracks by listening time
- Hourly listening patterns
- Weekly listening patterns
- Year-by-year listening hours

## Output

The notebook generates:
- Summary statistics (total hours/days listened)
- DataFrames with top artists, tracks, and artist catalogs
- Interactive plots using matplotlib and seaborn

## Privacy Note

This analysis uses personal streaming data. Ensure you have permission to share or publish any insights derived from your data. The JSON files contain sensitive information about your listening habits.

## Contributing

Feel free to fork this repository and enhance the analysis with additional insights, better visualizations, or machine learning models to predict listening patterns.

## License

This project is for personal use. Please respect Spotify's terms of service and data privacy guidelines.

## Acknowledgments

- Spotify for providing the Extended Streaming History feature
- The Python data science community for excellent libraries