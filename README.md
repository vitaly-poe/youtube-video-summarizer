# youtube-summarizer
Textual summary for a YouTube video by an URL given.

# Presumable scheme for the first-glance solution
Given URL -> Available captions / text-to-speech generated captions -> Text summarization.  

Somewhere in between descriptive features and videostream-generated features might be used.  

In terms of technical details, inference is processed on a cloud-hosted server or my personal PC through a web app, or a Telegram bot (witch is preferable).  

## Data
It seems reasonable to gather a dataset through YouTube API.  
For the first iteration, we'll ignore audio and video information.  
Features I presume to get for each video for the first iteration:
* URL
* Description
* All available captions
* Channel profile name
* [optional] Channel description

# Things to be done
* Build a python app in order to access YouTube API and be able to gather data  
* Research the text summarization models available  
* Brainstorm what can be done with the video in order to gather context, and how resource-consuming it might be.
* Build a Hello World Telegram bot
