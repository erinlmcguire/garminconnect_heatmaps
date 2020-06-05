# garminconnect_heatmaps
This repo contains the code that will parse one's activity data from Garmin Connect or Strava and then make a heatmap of the activities.  This will let you visualize your activity data to see how much of a location you have run, biked, or swam.  

I made this tool because I wanted to see how much of Atlanta I had run and have an easy way to update my progress.  All you need to make these heatmaps is a Garmin Connect (or Strava) account and a Google Maps API key.  You can download all your Garmin Connect data using kjkjava's repo here: https://github.com/kjkjava/garmin-connect-export

----------
Check out the analysis in the Jupyter notebook here. 

#Configuration
-----------------
-Create a folder called config, and put a file called "private.py" inside.    
  -Add a value called "API_KEY" that contains your Google Maps API Key.    
  -Add a two values called "garmin_username" and "garmin_password" that contain your Garmin Connect username and password.    
 
#Deployment
--------------
-Install Python 3 using Anaconda or another method.    
-Install Jupyter Notebook.    
-Install the Python requirements with pip install -r requirements.txt.    
-Run the program in Jupyter notebook.  Results will be shown inline and you can download the heatmap.    
