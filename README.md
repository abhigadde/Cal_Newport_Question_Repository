# Cal_Newport_Question_Repository

I always used to jump through Cal's podcast episodes to listen to the questions that interested me the most and I felt there should be a better way. I didn’t see a comprehensive list of questions he answered with timestamps and episode number so I thought I would build my own using python. I used the Spotify API and spotipy python library to get the episode descriptions and used the RegEx library to break apart the description into individual questions. I organized all of this into a pandas dataframe and outputted the final result as a csv.

This repo contains the code and the csv output of that code through episode 260 of his podcast. Feel free to run the code after getting your own spotify account and api tokens to update the excel file for future episodes.

I couldn’t quite get all the questions to come out cleanly (since I was using de-limit in python to split them apart) but I think it is of acceptable quality for not having done any manual edits myself. The biggest issues are episodes where he didn’t put time stamps for questions he responded to.

For any questions, feel free to contact me at abhinavgadde7@gmail.com

Note: If you open the csv file in the github viewer you have to scroll all the way to the right to see the url you need to click to get to the episode in spotify
