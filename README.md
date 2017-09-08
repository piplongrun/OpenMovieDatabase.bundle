Open Movie Database
===================
<img src="https://img.shields.io/github/release/piplongrun/OpenMovieDatabase.bundle.png?style=flat-square">

What is Open Movie Database?
----------------------------
Open Movie Database is a metadata agent for Plex Media Server that provides metadata for movies and TV shows. The current version of this agent works with *Plex Movie* and *The Movie Database* libraries for movies and *TheTVDB* for TV shows.

How do I install Open Movie Database?
-------------------------------------
You can install Open Movie Database:

 - From within the Unsupported AppStore, or:
 - Manually: See the support article "[How do I manually install a channel?](https://support.plex.tv/hc/en-us/articles/201187656-How-do-I-manually-install-a-channel-)" over at the Plex support website.

After installation:

1. Activate the agent in *Settings* > *Server* > *Agents*.
2. Use the *Refresh All Metadata* option on your library to let the agent collect and add metadata.

Where do I download Open Movie Database?
----------------------------------------
If you want to install the agent manually or if you are interested in the source code, you can download the latest copy of the agent from Github: [releases](https://github.com/piplongrun/OpenMovieDatabase.bundle/releases)

Where do I report issues?
-------------------------
Create an [issue on Github](https://github.com/piplongrun/OpenMovieDatabase.bundle/issues) and add as much information as possible:
 - Plex Media Server version
 - Primary agent and order of any secondary agents
 - Log files, `com.plexapp.agents.omdbapi.log`

What metadata can I expect from this agent?
-------------------------------------------

|                              | Movies | TV shows | Used by default | |
|------------------------------|:------:|:--------:|-----------------|-|
| Title                        | ✓      | ✓        | Yes             | |
| Year                         | ✓      |          | Yes             | |
| Plot                         | ✓      | ✓        | Yes             | |
| Content Rating               | ✓      | ✓        | Yes             | |
| Release Data                 | ✓      | ✓        | Yes             | |
| Genres                       | ✓      | ✓        | Yes             | |
| Production Company           | ✓      | ✓        | Yes             | |
| Directors                    | ✓      |          | Yes             | |
| Writers                      | ✓      |          | Yes             | |
| Actors                       | ✓      | ✓        | Yes             | |
| Runtime                      | ✓      | ✓        | Yes             | |
| Poster                       | ✓      | ✓        | No              | Just 1 poster image is available. Quality can vary, it is not recommended to use this. Use the Fanart.TV instead.|
| IMDb rating                  | ✓      | ✓        | Yes             | |
| ↳ Add to summary             | ✓      | ✓        | No              | |
| Rotten Tomatoes rating       | ✓      | ✓        | No              | |
| ↳ Add to summary             | ✓      | ✓        | No              | |
| Metacritic rating            | ✓      |          | No              | |
| ↳ Add to summary             | ✓      |          | No              | |
