# youtube_data_harvesting
This is my first project based on EDA project using a pandas, mongodb, mysql, streamlit
Problem Statement:
The problem statement is to create a Streamlit application that allows users to access and analyze data from multiple YouTube channels. The application should have the following features:
  Ability to input a YouTube channel ID and retrieve all the relevant data (Channel name, subscribers, total video count, playlist ID, video ID, likes, dislikes, comments of each video) using Google API.
 Option to store the data in a MongoDB database as a data lake.
 Ability to collect data for up to 10 different YouTube channels and store them in the data lake by clicking a button.
 Option to select a channel name and migrate its data from the data lake to a SQL database as tables.
Ability to search and retrieve data from the SQL database using different search options, including joining tables to get channel details.
Approach: 
Set up a Streamlit app: Streamlit is a great choice for building data visualization and analysis tools quickly and easily. You can use Streamlit to create a simple UI where users can enter a YouTube channel ID, view the channel details, and select channels to migrate to the data warehouse.
Connect to the YouTube API: You'll need to use the YouTube API to retrieve channel and video data. You can use the Google API client library for Python to make requests to the API.
Store data in a MongoDB data lake: Once you retrieve the data from the YouTube API, you can store it in a MongoDB data lake. MongoDB is a great choice for a data lake because it can handle unstructured and semi-structured data easily.
Migrate data to a SQL data warehouse: After you've collected data for multiple channels, you can migrate it to a SQL data warehouse. You can use a SQL database such as MySQL or PostgreSQL for this.
Query the SQL data warehouse: You can use SQL queries to join the tables in the SQL data warehouse and retrieve data for specific channels based on user input. You can use a Python SQL library such as SQLAlchemy to interact with the SQL database.
Display data in the Streamlit app: Finally, you can display the retrieved data in the Streamlit app. You can use Streamlit's data visualization features to create charts and graphs to help users analyze the data.
Overall, this approach involves building a simple UI with Streamlit, retrieving data from the YouTube API, storing it in a MongoDB data lake, migrating it to a SQL data warehouse, querying the data warehouse with SQL, and displaying the data in the Streamlit app.
SQL Query Output need to displayed as table in Streamlit Application:
What are the names of all the videos and their corresponding channels?
Which channels have the most number of videos, and how many videos do
 they have?
What are the top 10 most viewed videos and their respective channels?
How many comments were made on each video, and what are their
 corresponding video names?
Which videos have the highest number of likes, and what are their 
corresponding channel names?
What is the total number of likes and dislikes for each video, and what are 
their corresponding video names?
What is the total number of views for each channel, and what are their 
corresponding channel names?
What are the names of all the channels that have published videos in the year
 2022?
What is the average duration of all videos in each channel, and what are their 
corresponding channel names?
Which videos have the highest number of comments, and what are their 
corresponding channel names?
Results: 
This project aims to develop a user-friendly Streamlit application that utilizes the Google API to extract information on a YouTube channel, stores it in a MongoDB database, migrates it to a SQL data warehouse, and enables users to search for channel details and join tables to view data in the Streamlit app.
Project Evaluation metrics:
You are supposed to write a code in a modular fashion (in functional blocks)
Maintainable: It can be maintained, even as your codebase grows.
Portable: It works the same in every environment (operating system)
You have to maintain your code on GitHub.(Mandatory)
You have to keep your GitHub repo public so that anyone can check your code.(Mandatory)
Proper readme file you have to maintain for any project development(Mandatory)
You should include basic workflow and execution of the entire project in the readme file on GitHub
Follow the coding standards: https://www.python.org/dev/peps/pep-0008/
You need to Create a Demo video of your working model and post in LinkedIn(Mandatory)
