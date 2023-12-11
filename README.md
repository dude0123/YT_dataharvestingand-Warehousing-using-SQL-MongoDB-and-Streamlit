# YT_dataharvestingand-Warehousing-using-SQL-MongoDB-and-Streamlit

The task is to build a Streamlit app that permits users to analyze data from multiple YouTube channels. Users can input a YouTube channel ID to access data like channel information, video details, and user engagement. The app should facilitate storing the data in a MongoDB database and allow users to collect data from up to 10 different channels. Additionally, it should offer the capability to migrate selected channel data from the data lake to a SQL database for further analysis. The app should enable searching and retrieval of data from the SQL database, including advanced options like joining tables for comprehensive channel information.

## Steps Taken
Start by setting up a Streamlit application using the python library "streamlit", which provides an easy-to-use interface for users to enter a YouTube channel ID, view channel details, and select channels to migrate.
Establish a connection to the YouTube API V3, which allows me to retrieve channel and video data by utilizing the Google API client library for Python.Once you retrieve the data from the YouTube API,
Store the retrieved data in a MongoDB data lake, as MongoDB is a suitable choice for handling unstructured and semi-structured data. 
Transfer the collected data from multiple channels namely the channels,videos and comments to a SQL data warehouse.
Utilize SQL queries to join tables within the SQL data warehouse and retrieve specific channel data based on user input. For that the SQL table previously made has to be properly given the the foreign and the primary key.

