# Python DJ
A music streaming application that allows you to invite others to your DJ booth or music lounge

Tech Used
HTML
CSS3
React.js
Django
Python 3
Material UI

# Future Enhancements
Integrate third party music API
add a chat for each lounge created

## Screen Shots of app on local server
Here is the landing page. AAU, there are 2 entries into the site, if user has a unique key, user will choose "JOIN A DJ BOOTH" (will explain that function more in upcoming screen shots). Choose "CREATE A DJ BOOTH" to create a music lounge and set the settings for others to join.
![Screen Shot 2021-01-22 at 6 09 24 PM](https://user-images.githubusercontent.com/73125103/105558713-2d272500-5cdd-11eb-917d-333a4b9a7d83.png)


Once "CREATE A DJ BOOTH" is clicked, it will bring user to the following screen shot. If permissions are set to "play/pause", users who join the dj booth will have those permissons over the music player along with a "Vote to skip song" function. If permissions are set to "No Control", the only option users will have will be to "Vote to Skip". This "Vote to skip" function is great if you're hosting a party and invite mixed groups of friends and not sure what the agreeable music vibe is. The admin/host has the feed back immediately if the joined users vote to skip. 
![Screen Shot 2021-01-22 at 6 09 33 PM](https://user-images.githubusercontent.com/73125103/105558903-d0783a00-5cdd-11eb-8426-45f67653ff6f.png)

Everytime a "DJ BOOTH" is created, an unique key is also made. (THIS WAS MY FAVORITE CODE TO LEARN AND WRITE IN THIS APP! This code can be found in api/models.py). Once administered by the dj booth creator, this allows other users to enter the music lounge via the "JOIN A DJ BOOTH" link which then brings them to a page where the unique key needs to be entered in order to give them access to join the desired music lounge.

![Join-a-room](https://user-images.githubusercontent.com/73125103/105560552-16370180-5ce2-11eb-9aad-492c65174c69.png)









