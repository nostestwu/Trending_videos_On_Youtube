# Trending_videos_On_Youtube

## Trending on YouTube ##
Trending helps viewers see what’s happening on YouTube and in the world. Trending aims to surface videos and shorts that a wide range of viewers would find interesting. Some trends are predictable, like a new song from a popular artist or a new movie trailer. Others are surprising, like a viral video.

Trending isn't personalized and displays the same list of trending videos to all viewers in the same country, which is why you may see videos in Trending that aren’t in the same language as your browser. However, in India, Trending displays a list of results for each of the 9 most common Indic languages.

## SOURCE ##
The data has been scrapped from "Mendeley.com". The source of this file ishttps://data.mendeley.com/datasets/7pkbvjtnxm/1/files/e7763107-45e9-4613-8c81-146e6a272266
Converted the data to csv file to use it in kaggle ../input/youtube-vdos/youtube trending videos dataset.csv

## Result ##
Personally I have created different graphs based on the views, likes and categories to see any relations. The result shows that the majority of people in India are far more interested in watching Science & Technology than other categories. Most commented channel is News & Politics which is expected due to the argument between different sides. Lastly, I found out the most watched videos are all within the time interval between 7 to 13 minutes. Surprisingly this video time length is suggested and used by many youtubers. If more datasets are given, we might be able to find the golden time for making youtube videos.

## The data contains following columns ##

1) Position (int type) - An index column which gives the position of the channel in youtube channel
2) Channel Id ( Stirng ) - ID of the youtube channel
3) Channel Title ( String ) - Youtube channel title
4) Video Id (String) - ID of video in the youtube channel
5) Published At (String) - date of the video published at
6) Video Title (String ) - Title of the video
7) Video Description (String) - Description of the video(what the video is about)
8) Video Category Id ( int type) - Category of the video in youtube channel
9) Video Category Label (String) - type of category the video belongs
10) Duration (String ) - duration of the video
11) Duration Sec ( int type) - Duration of video in seconds
12) Dimension (String) - Dimension of the video (2D , Hd)
13) Definition (String) - Defining the video
14) Caption (bool ) - Boolean type caption (True or False)
15) Licensed Content (float Type)
16) View Count ( int type) - number of people viewed the video
17) Like Count (float) - Number of likes the channel got
18) Dislike Count (float) - Number of dislikes the channel got
19) Favorite Count ( int type) - Number of people marked as favourite
20) Comment Count (float) - Number of people commented on the video
