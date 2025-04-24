# Music Industry Investigation

**AUTHOR:** Matthew Thoomkuzhy

**CANDIDATE NUMBER: 50798** 
---
**\#TODO:**


- [x] **An Image representing the project**

![alt text](data/Projectlogo.jpg)
(Generated Using Chatgpt)
---

- [x] **Brief description of repository**

This repository documents code regarding my investigation of the music industry. When I first started I wanted to find out whether there were underlying trends in the relationships between the top 100 most listened to artists.

So I collected the following data for the top 100 artists of 2023:

- General artist information name, followers, genre(s)
- Information about which other top 100 artists were related to them
- Information about the top tracks of each of the top 100 artists

*I ended up answering 2 questions using insights from my visualisations:*

1. What influences the formation of communities in the music Industry?
2. Do the top 100 artists act like monopolists?

- I created network diagrams for insights on relationships between artists by spotify's related lists and by linking artists who had common genres.
- I created a heatmap to show which artists had collaborated on tracks the most within the top 100
- I created a lorenz curve to show the inequality of followers between the top 100 artists
- I created a bar chart to investigate trends in song duration
- I created a pie chart to investigate the relative share of followers of the top 100 artists
---


- [x] **Instructions of how to recreate virtual environment in pyenv:**

1. Open terminal and check you have python installed by typing: python --version
2. cd to where you want to recreate the files and type: python -m venv venv
3. Depending on your terminal language activate the virtual envrionment
4. Use the requirements.txt, copy this file into your desired driectory and type: pip install -r requirements.txt
5. Verify installation by typing: pip list (this lists packages installed and their versions)
---



- [x]  **Instructions for how to obtain the Spotify API credentials and where to put them**

1. Create your own spotify account and go on spotify for developers and obtain the following information and save it in a .env file, which contains the following information as follows:

  - SPOTIFY_USERNAME = #your_info
  - SPOTIFY_PASSWORD = #your_info
  - SPOTIFY_CLIENT_ID = #your_info
  - SPOTIFY_CLIENT_SECRET= #your_info

2. After storing the .env in your directory,  open the notebook titled 'NB01-Data_Collection', and run the code titled 'activate api token'

3. The API token is stored in a get method get_token(), call the function whenever you want to access your token
---

- [x] **Instructions for how to run the code and replicate the results**

After ensuring all necessary files are added, run the notebooks in the following order:

 1. code/NB01-Data_Collection
 2. code/NB02-Data_Processing
 3. code/NB03-Data_visualisation

**Update**: The related artists API was depracated so reproduction of the file titled 'T100_related_artists_count.json' via the code block in NB01 will not work. 
The file needs to be saved manually and added to your repository.

My findings along with my graphs appear in the data visualisation notebook. The graph images can be accessed seperately as they are listed as png's in the data/visualisations/ folder.

### **ENJOY!**




#
