# 30daysleaderboard

I made this for the program #30DaysofGoogleCloud

For this you need to edit all the Qwiklabs Public URL  in the userurl.txt and run publiclistmaker.py to generate all the links in list and update the list in main.py
It has multi threading support and it scrapes the data in 6 seconds and it will automatically run on github action every 2 hours to scrap the data and generate JSON file.
For hosting use netlify

Note - Make sure all the Qwiklabs public URL are correct otherwise it will crash.
Also you need to manually scrap and push the data to Github, the netlify will get auto trigger and will update the site in 2 seconds.

Thank You
