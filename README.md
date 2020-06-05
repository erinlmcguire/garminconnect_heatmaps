# garminconnect_heatmaps
This repo contains the code that will parse one's activity data from Garmin Connect or Strava and then make a heatmap of the activities.  This will let you visualize your activity data to see how much of a location you have run, biked, or swam.  The color palette of the heatmap is customizeable.

I made this tool because I wanted to see how much of Atlanta I had run and have an easy way to update my progress.  All you need to make these heatmaps is a Garmin Connect (or Strava) account and a Google Maps API key.  You can download all your Garmin Connect data using kjkjava's repo here: https://github.com/kjkjava/garmin-connect-export

----------
Check out the analysis in the Jupyter notebook here. 

# Configuration
-------------------
-Export all of your activities as gpx manually or using one of the scripts on Github.  Strava also has a tool to download all your activity data.
-Add your Google Maps API key to the code     
-Update the directory that contains the gpx activity files
 
# Deployment
--------------
-Install Python 3 using Anaconda or another method.    
-Install Jupyter Notebook.    
-Install the Python requirements with pip install -r requirements.txt.    
-Run the program in Jupyter notebook.  Results will be shown inline and you can download the heatmap.    

# Example Files
-------------------------------
Two example of the output heatmap are included:      
  -"atlanta_heatmap1"      
  -"tucson_heatmap"    
