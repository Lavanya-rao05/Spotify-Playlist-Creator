# Spotify-Playlist-Creator

Spotify Playlist Creator from Billboard 100
This Python script automates the creation of Spotify playlists using Billboard's top 100 songs from any date in the past. It leverages the Spotify API and Spotipy library for seamless integration.

1. Setup Instructions
  Sign Up for Spotify Developer Account
  If you haven't already, sign up for a Spotify account and then register as a developer on the Spotify Developer Dashboard.    https://developer.spotify.com/

2. Create a Spotify App 
  Create a new Spotify App on the Developer Dashboard with the following details:
  App Name: Billboard 100
  App Description: Takes top 100 music from a specified date to create a Spotify Playlist.
  Redirect URI: http://example.com
  
3. Copy Client ID and Client Secret
  After creating the app, copy the Client ID and Client Secret into your Python script.

4. Run the Python Script
  Execute the Python script and enter the date in the format YYYY-MM-DD when prompted.
  Follow the authentication flow to grant necessary permissions to your Spotify account.
  Once authenticated, copy the entire URL from the redirected page and paste it into the console.

5.Playlist Creation
  The script will fetch Billboard's top 100 songs from the specified date and create a new private playlist in your Spotify account.
