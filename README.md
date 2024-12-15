# CrowdDJ
![Screenshot 2024-12-15 095330](https://github.com/user-attachments/assets/d627118b-b16c-46c2-b4ca-ea38db2040d1)
CrowdDJ is a program which controls your spotify queue. Its great for parties where guests can add their own songs to the queue with a simple to use Ui.

# Setup
1. Run ```pip install spotipy``` to install the Spotipy library
2. Go to [Spotify Developer Dashboard](https://developer.spotify.com/dashboard) and create a new app
3. Add https://localhost:8888/callback to the redirect URIs
4. Copy the Client Id and Client Secret for the next step
5. Download the files and replace "YOUR-CLIENT-ID" with the Client Id and "YOUR-CLIENT-SECRET" with the Client Secret
6. Run the code and go to http://localhost/ or your devices ip address
7. On the first run it will automatically open a page up which will redirect you to a url. Copy this url and go back to your code and paste it in when it asks for it
Done! Enjoy the at home version of CrowdDJ

# Optional Extra
I recommend checking out the [CYD catalogue by witnessmenow](https://github.com/witnessmenow/ESP32-Cheap-Yellow-Display) and purchasing one to use it as a spotify playback controller using [Spotify DIY Thing by witnessmenow](https://github.com/witnessmenow/Spotify-Diy-Thing). This is handy when you are the host of the party and SOMEONE has added the most awfull song ever. You can use the device to skip over it or rewind. Thank you for checking this out btw (although I doubt anyone will actually see this).
