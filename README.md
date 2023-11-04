# Taylor-Swift-Song-Recommender

In this project, I look at Taylor Swift's songs through the lens of data science with data on both the lyrics and audio qualities of Taylor Swift's musical body of work. I work with Python and Pandas to build data visualizations, a song recommender, lyric searcher, and word cloud for text data within lyrics.

The datasets used contain all songs on each of Taylor Swift's [ten studio albums](https://en.wikipedia.org/wiki/Taylor_Swift_albums_discography#Studio_albums). I've chosen to use deluxe or extended versions of these albums when available, to include more songs, but have eliminated duplicate versions of songs, such as acoustic versions and remixes. I've also chosen to include the rerecorded "[Taylor's Version](https://www.vox.com/culture/22278732/taylor-swift-re-recording-1989-speak-now-enchanted-mine-master-rights-scooter-braun)" when available. The datasets don't include Taylor Swift songs that were released as part of movie soundtracks, live recordings, holiday specials, or through any other mechanism.

I generally work with two DataFrames throughout the project:
- The `lyrics` DataFrame contains the lyrics of each Taylor Swift song.  The data in `lyrics` comes from [Genius](https://genius.com/), "the world's biggest collection of song lyrics and crowdsourced musical knowledge."
- The `tswift` DataFrame contains information about the audio features of each song. The data in `tswift` comes from [Spotify](https://open.spotify.com/). 
