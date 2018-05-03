# make-your-own-Spotify-playlist-of-playlist-recommendations

This code snippet helps you create your own Spotify public playlist containg recommended tracks for each track in a source public playlist using Spotipy library.

Here is the original library;
[Spotipy Documentation](http://spotipy.readthedocs.org/)
[Spotipy GitHub repo](https://github.com/plamere/spotipy)

You should first create a Spotify web API via [Spotify for Developers](https://beta.developer.spotify.com/)
Get your APP credentials to provide into the code;

You should get and set the following information first

cid =' ' # Client ID; copy this from your app
secret = ' ' # Client Secret; copy this from your app
username = ' ' # Your Spotify username

#for available scopes see https://developer.spotify.com/web-api/using-scopes/
scope = 'user-library-read playlist-modify-public playlist-read-private'

redirect_uri=' ' # Your app URL
