# Data
This project utilizes data scraped from Spotify's genre-specific playlists and includes information such as song title, artists(s), and album image URL. The genres considered were Pop, Dance, Indie, Rock, Soul, Country, and K-Pop.

From the URLs, the images were downloaded and converted to image vectors using OpenCV. Black and white images were filtered out, and images that didn't have a dimension of (300,300,3) were padded. 

Unfortunately, the data frame with these final vectors could not be saved as a csv file. Refer to the `notebook` folder in this repository for code relevant to this process.