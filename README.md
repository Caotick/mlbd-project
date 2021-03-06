# CS-421 Project

This is the repository of the project for the CS-421 course.

Requiered libraries :

* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Spotipy (if you wish to replicate the Spotify API's queries)

In order to replicate our experiments, you need:

* The last-fm360k dataset which is downloadble [here](http://ocelma.net/MusicRecommendationDataset/lastfm-360K.html).
* The 'full_spotify_info.csv' file which was obtained using the Spotify API. The file is already provided in the data folder of the repo. It can be recreated using spotify_api.ipynb. To do so, you will need create a file called credentials.py containing 2 variables named clientId and clientSecret set to the credentials of your spotify account, which can be obtained when going on the [dashboard](https://developer.spotify.com/dashboard/), logging in, and creating a new app, and then run the entire spotify_api.ipynb notebook.
* The groups that were generated using the create_groups notebook. The groups used to assess the methods are already in the data folder.


To replicate our experiments, you can just run the cells of the mlbd-project notebook in order.

Here is the link to our github repo: https://github.com/Caotick/mlbd-project/tree/main