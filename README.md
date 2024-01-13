# Video Summarizer
## About
This tool uses ChatGPT to summarise a YouTube video by providing either a YouTube channel or the video link.

It will provide a brief 150 word summary of the video as well as the top 5 main points in the video.
The main points are timestamped so that it's easy to navigate the video where
the conversation is taking place. 

This tool as allows one to determine whether to summarise the entire video or
a portion of the video - the first 25% of the video being the default.

## Installation
- Clone this repo
- Set up Python 3.10 in a vitual environment
- Install packages: `pip install -r requirements.txt`
## Usage
- Update `video_urls.yaml` with the videos to summarise
- Update `src/params.yaml` (optional)
- Run `main.py`
- Video summaries will be saved under: `video-summarizer/files/summaries/`

## Sample summary
![Sample video summary](./Screenshot.png)