# htgaws
R code for the four 2D interactive games described in "How to Gent Away with Statistics: Gamification of Multivariate Statistics"

# Modifying the default data of a game
To modify the default data of a game:
1) put your new default data in the "data" folder
2) modify the app.R file, precisely in the first line of the server function (# available data mydata <- read.table(file="data/NEWDEFAULTDATASET", sep=',', header=TRUE))
