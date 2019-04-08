# LIRI NODE APP

LIRI is a Language Interpretation and Recognition Interface. This CLI (Command-Line interface) application takes in command parameters to gives back data by searching through designated APIs. This LIRI will search through these APIs: Spotify, Bands in Town and OMDB for songs, concerts, and movies.

**Required NPMs:**
- Node-Spotify-API
- Axios
- Moment
- DotEnv

## How to use:
Type the following in your terminal or git bash:
**node liri command keyword** 
  1. node liri concert-this : this searches for concerts for a specific band or artist.
  2. node liri spotify-this-song :this looks up details for a specific song through its title
  3. node liri movie-this : this look look up details for a specific movie through its title
  4. node liri do-what-it-says : displays what is listed on the random.txt 
 
  
 ## Demo ##
 
 [Video Demo] (https://drive.google.com/file/d/1WQGqTy2eJ_zuA0ud66fEXGMvRo3VyZxk/view?usp=sharing)
 

If a keyword is not used the default result will be :
1. for concert it will be blank
2. for spotify will be "The Sign" by the Ace of Base
3. for movie  is 'Mr. Nobody'
4. for do-what-it-says there is no keyword to begin with 


