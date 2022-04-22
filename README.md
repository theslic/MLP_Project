# MLP_Project Dataset Description
- Prediction of music genre:
    - Dataset description: The full list of genres included in the CSV are 'Electronic', 'Anime', 'Jazz', 'Alternative', 'Country', 'Rap', 'Blues', 'Rock',             'Classical', 'Hip-Hop'.
    - Attributes description:
        Instance_id (float): unique id for each music
        Artist_name (string): artist name for each track 
        Track_name (string): name for each track
        Popularity (float): how popular this music
        Acousticness (float): how acoustic the music is
        Danceability (float): how danceable the music is
        Duration_ms (float, negative and positive): the duration of the music in milliseconds
        Energy (float): energy of the music
        Instrumentalness (float): how instrumental the music is
        Key (string): music key of each track
    - Size of dataset: 10 columns and 41700 unique values
- Prediction based on popularity
    - The dataset contains the top songs on Spotify
    - Attributes:
        Index(int): the number of the song
        Highest Charting Position(int): The highest the song has been on the popularity list
        Number of Times Charted(int): How many times the song has been on the charts
        Week of Highest Charting(date): Date range of the week the song was most popular
        Song Name(string): The name of the song
        Streams(int): The number of times it has been played
        Artist(string): The name of the artist of the song
        Artist Followers(int): How many followers the artist of the song has
        Song ID(string): Unique identifier for each song
        Genre(list): The list of genres the song falls under
    - The size of the dataset is 1556 rows and 23 columns
