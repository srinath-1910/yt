# YouTube Data Harvesting and Analysis

This project leverages the YouTube Data API to harvest and analyze data from multiple YouTube channels. It enables users to gather insights about channel performance, video statistics, and engagement metrics.

## Features
- Collect data from multiple YouTube channels using channel IDs.
- Extract details such as video titles, descriptions, views, likes, and more.
- Analyze trends and visualize data using Python libraries like `pandas` and `seaborn`.

## Requirements
To run this project, ensure you have the following:
- Python 3.7 or later
- Google YouTube API Key
- Required Python libraries:
  - `googleapiclient`
  - `pandas`
  - `seaborn`

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/youtube-data-harvesting.git
   cd youtube-data-harvesting
   ```

2. **Install the required libraries**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up the Google YouTube API**
   - Obtain an API key from the [Google Cloud Console](https://console.cloud.google.com/).
   - Enable the YouTube Data API v3 for your project.

4. **Configure the API key**
   Replace `api_key` in the notebook with your own API key:
   ```python
   api_key = 'YOUR_API_KEY'
   ```

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Youtube data harvesting.ipynb"
   ```

2. Replace the default `channel_ids` list with your own:
   ```python
   channel_ids = [
       'CHANNEL_ID_1',
       'CHANNEL_ID_2',
       # Add more channel IDs as needed
   ]
   ```

3. Run the notebook cells sequentially to:
   - Connect to the YouTube API.
   - Fetch and process data from specified channels.
   - Visualize and analyze channel and video performance.

## Example Visualizations
- Channel comparison by total views.
- Video trends over time.
- Engagement metrics such as likes and comments per video.

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch.
3. Submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments
- [Google YouTube API](https://developers.google.com/youtube/v3)
- Python open-source community
