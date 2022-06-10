# YouTube Data Analysisy

## Process
1. List all the required channel's id 
2. Using build from googleapiclient.discovery build python representation 
3. A function to get channel's statistics
4. Convert obtained data into pandas dataframe
5. Convert string into numerical values such as views, subcribes, total_videos 
6. Start plotting the graphs such as
    - Channel name vs Subs
    - Channel name vs Views
7. A function to get a videos id's 
```playlist_id= channel_data.loc[channel_data['channel_name']=='Mrwhosetheboss', 'playlist_id'].iloc[0]```
8. Function to get video details
9. Again convert into numeric ( not all )
10. Sort video data into top 10
11. Plot the graphs to understand it better
12. Calculate videos per month
13. Analyse the barchart to know in which month creator posted more videos
14. Save all the details into a .csv file by ```video_data.to_csv('Video_Details(MRWhoseTheBoss).csv')```
