
# HARM Bot - A YouTube API Bot

HARM Bot is a Streamlit application that provides various features related to YouTube videos and channels, such as predicting the category of educational videos, viewing channel statistics, searching for videos, predicting categories for playlist videos, and estimating the educational content percentage in a video.

## Getting Started

Follow these steps to get the HARM Bot up and running on your system.

### Prerequisites

Before you begin, make sure you have Python 3 version below 3.10 (best supported for 3.9) installed on your system. You can download Python from [the official Python website](https://www.python.org/downloads/release/python-3109/).

### Installation

You can [download the source code as a ZIP file](https://drive.google.com/file/d/1Phlp0ovhml0VIU0T2pT69aM0Zrbk7vFs/view?usp=share_link) and extract it.

2. Change to the project directory:

Navigate to the extracted folder.
```
cd HARM
```

 3. Virtual environment has been already created named `venv` for you. If you don't see it, create it using the below command
```
python -m venv venv
```

 4. Activate the virtual environment:

- On Windows:
  ```
  .\venv\Scripts\activate
  ```

- On macOS and Linux:
  ```
  source venv/bin/activate
  ```

### Note# _If you are using an Operating System other than MacOS with m1, or m2 processors, you have to remove the last line in the requirements.txt file `--no-cache-dir  --force-reinstall  --prefer-binary pyarrow` before proceeding to next step._

5. Install the required packages:
```
pip install -r requirements.txt
```

### Running the Application

To run the HARM Bot Streamlit application, execute the following command in the terminal:

```
streamlit run app.py
```
This will start the Streamlit server, and the HARM Bot application will open in your default web browser.

## Usage

The HARM Bot application provides several features that can be accessed from the sidebar menu:

1. **Category Predictor**: Enter the URL of a YouTube video, and the bot will predict the category of the video if it's educational.
2. **Channel Stats Viewer**: Enter the URL of a YouTube video, and the bot will show the statistics of the video's channel.
3. **Search Videos**: Search for YouTube videos by entering keywords.
4. **Playlist Videos Predictor**: Enter a YouTube playlist URL, and the bot will predict the categories of the videos in the playlist if they are educational.
5. **Educational Content in a Video**: Enter a YouTube video URL, and the bot will estimate the percentage of educational content in the video.

## Contributing

If you'd like to contribute to this project, please feel free to submit a pull request or open an issue on the GitHub repository.

## License

This project is licensed under the MIT License.

## Acknowledgements

Special thanks to the HARM team for creating this application:

- Harshul Nanda
- Abhijeet Saroha
- Rishabh Sagar
- Mayank Arora

You can find more information about the team and the project on the [HARM LinkedIn page](https://www.linkedin.com/company/82157293/admin/).
