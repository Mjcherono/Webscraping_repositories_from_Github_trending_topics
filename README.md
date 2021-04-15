# Webscraping_repositories_from_Github_trending_topics
I will scrape https://github.com/topics
Get a list of topics. For each topic, I will get the topic title, topic page URL and topic description
For each topic, I'll get the top 25 repositories in the topic from the topic page
For each repository, I'll grab the repo name, username, stars and repo URL
For each topic I'll create a CSV file in the following format:
Repo Name,Username,Stars,Repo URL
three.js,mrdoob,69700,https://github.com/mrdoob/three.js
libgdx,libgdx,18300,https://github.com/libgdx/libgdx
