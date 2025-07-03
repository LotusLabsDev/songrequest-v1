# Proof of concept for [SongRequest](https://songrequest.lotuslabs.dev)

This is a simple website and backend to listen to one twitch streamers chat to listen out for a channel point redemption, and then take that input and search the spotify api to get a song, then if a song is found, put that information into a supabase database. This links to a HTML, CSS, and JS page where moderators can approve or deny songs, once approved, the song gets added to the streamer's playback queue on spotify.

This concept works; however, it is not secure... It shows supabase keys in the frontend code, as well as the login just being a check to another table in the supabase db for username and password. Again, proof of concept
