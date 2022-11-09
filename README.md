# football-app
Welcome to this my first football web app, developed with R shiny. I constructed a dissimilarity measure to compare football's players based on their performances in season 2014-2015. The app works as a football players dissimilarity query. After computing and saving a dissimilarity matrix with the weights you will give of a list of football actions in the first navigation bar page, load that matrix in the query page and choose the player of your interest. Then the app will return you the players most similar to the player of your interest. 

The raw dataset I use, which contains informations about 3003 players described with 109 variables, is available as .csv file in the folder data/. You can check the app user interface code source in the file ui.R and the server code source in server.R.

You can test a simple version of the app on this link : https://achadj.shinyapps.io/football-app/
