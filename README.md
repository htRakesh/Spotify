The following functions added to Spotify web application:

1.**Created user**
2.**Created artist**
3.**Created album**
4.**Created song**
5.**Created playlist based on length**: This API creates a new playlist with a given title and adds all songs with a given length to the 
  playlist. The creator of the playlist is the given user, who is also the only listener at the time of playlist creation.
6.**Created playlist based on name**: This API creates a new playlist with a given title and adds all songs with the given titles to the 
  playlist. The creator of the playlist is the given user, who is also the only listener at the time of playlist creation.
7.**Find playlist**: This API finds a playlist with a given title and adds the given user as a listener to that playlist. If the user is the 
  creator or already a listener, it does nothing.
8.**Like song**: This API allows a user to like a given song, which also auto-likes the corresponding artist. If the user has already liked the 
  song, it does nothing.
9.**Most popular artist**: This API returns the artist with the maximum number of likes.
10.**Most popular song**: This API returns the song with the maximum number of likes.
