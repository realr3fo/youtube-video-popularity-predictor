# Youtube Popularity Predictor

This source code is a documentation on the work for predicting youtube video popularity for research method class.

To run the code, you need to download the dataset from kaggle through [this link](https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset)

And then once downloaded, change the first line of the `US_youtube_trending_data.csv` file into the following:
`video_id,title,publishedAt,channelId,channel_title,category_id,trendingAt,tags,views,likes,dislikes,comment_count,thumbnail_link,comments_disabled,ratings_disabled,description`

This is to avoid any error while cleaning the dataset within the code.