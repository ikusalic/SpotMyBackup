# Personal instructions

python -m SimpleHTTPServer 8888
http://localhost:8888/index.html

More info:
https://github.com/secuvera/SpotMyBackup/wiki

Track api:
https://developer.spotify.com/documentation/web-api/reference/tracks/get-track/

In original version of the code only id and uri fields are exported. This could be relevant if I ever try to import those backups.


# SpotMyBackup

Backup and Restore your Spotify Playlists and "My Music".

This javascript based app allows you to backup all your playlists and import them in any other Spotify Account. It uses the OAuth-Functionality of Spotify to be able to handle your personal playlists. 

In consequence, no credentials or data is stored or processed on the Webserver itself.

You can use it at www.spotmybackup.com or on your own webserver (see Q&A).
