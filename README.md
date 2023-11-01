# YouTube_Data_Harvesting_and_Warehousing1.
Extract information from a specific YouTube channel by utilizing its YouTube ID Using Python with Pandas, SQL and MongoDB  After fetching the data, you can analyze it based on a set of questions from the user. Additionally, you can use MySQL to store the extracted data and Streamlit to create interactive visualizations for better insights.


This project extracts the particular youtube channel data by using the youtube channel id using  youtubeAPI Key and data source
 Then the data is processed  and stored  in the MongoDB database 
 From MongoDB database  it  has the option to migrate the data to MySQL for structured data 
 Analyse the data and give the results depending on the customer questions.


 **Tools Installed for this Project** :
-Virtual code.
-Jupyter notebook.
-Python 3.11.0 or higher.
-MySQL.
-MongoDB.
-Youtube API key.


**The  Libraries Required for project  to Install**
pip install google-api-python-client

pymongo 

mysql-connector-python

sqlalchemy

 pandas 
 
 streamlit.
( pip install google-api-python-client ,pymongo ,mysql-connector-python ,sqlalchemy, pandas ,streamlit )


**ETL Process for the Project **
Step 1 :  Extract data from particular youtube channel by using the youtube channel id, with the help of the youtube API developer console.

Step 2: Once the extraction process is done take the required data and transform it into JSON format by inserting into the MongoDB database

Step 3: Since the data  is in unstructed format , migrate the data to MySQL database from the MongoDB database for getting the structured data for analysis

**EDA Process for the project** :
Step 1: Filter and process the structured data from the tables depending on the given requirements by using SQL queries and transform the structured data into a DataFrame format.

**Visualization process for the project**:
Finally, create a Dashboard by using Streamlit and give dropdown options on the Dashboard to the user and select a question from that menu to analyse the data and show the output in Dataframe Table .



**User Guideline:**
Step 1 : **DATA COLLECTION **

       Search channel_id  from Youtube  and  copy and paste on the input box and click the  button in the Data collection zone which will upload the data in MongoDB Database
       
Step 2 : **INSERTING DATA INTO MYSQL **

        Select the channel name and click the Upload data  to MySQL button to migrate the specific channel data to the MySQL database from MongoDB .
        
Step 3 : **SELECT THE REQUIRED QUESTION TO GET INSIGHTS FROM DATA **

         Select a Question from the dropdown option you can get the results in Dataframe format.
