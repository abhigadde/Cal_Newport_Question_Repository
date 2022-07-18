# Cal_Newport_Question_Repository

I always used to jump through Cal's podcast episodes to listen to the questions that interested me the most and I felt there should be a better way. I didn’t see a comprehensive list of questions he answered with timestamps and episode number so I thought I would build my own using python. I used the Spotify API and spotipy python library to get the episode descriptions and used the RegEx library to break apart the description into individual questions. I organized all of this into a pandas dataframe and outputted the final result as a csv.

I couldn’t quite get all the questions to come out cleanly (since I was using de-limit in python to split them apart) but I think it is of acceptable quality for not having done any manual edits myself. The biggest issues are episodes where he didn’t put time stamps for questions he responded to.

I sent over the code to Cal to see if he could publish it for everyone to see. However 2 weeks later and no response yet. Also he changed the formatting of his episode descriptions for episodes 204+, breaking this code for future episodes. Is this just a co-incidence?
