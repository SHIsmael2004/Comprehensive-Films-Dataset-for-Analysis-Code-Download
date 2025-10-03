About Dataset
Description
The dataset is a thorough compilation of data about movies that includes both qualitative and quantitative characteristics. Every record reflects a distinct film and offers information about its identity, genre, release date, country of production, financial performance, audience reaction, and major players.

Important points to note are:
Identifiers and Metadata:Unique movie IDs, titles, genres, and release details.

Financial Indicators:Early sales performance, domestic (U.S.) and international box office performance, and budget.

Audience and Critical Reaction:Rotten Tomatoes scores, IMDb ratings, and the number of votes that go along with them.

Contributors:Details about the director and the main actor.

This dataset works well with:
Exploratory Data Analysis (EDA):Finding trends in the popularity, profitability, and creation of films.

Predictive Modeling:Forecasting financial success, ratings, or audience engagement.

Comparative Studies: Examining patterns in various genres, nations, and years of publication.

Recommendation systems use votes and ratings to sugest films.

This dataset offers a solid basis for data analysis, visualization, and machine learning applications in the film industry by providing a well-balanced combination of descriptive, financial, and evaluative information.


Type of target:
🎯 Colonnes numériques (liées au succès commercial)

US_BoxOfficeUSD → prédire le box office US.

Global_BoxOfficeUSD → prédire le box office mondial.

Opening_Day_SalesUSD ou One_Week_SalesUSD → prédire les ventes du lancement.

BudgetUSD → tu pourrais prédire le budget, mais ça n’a pas trop de sens car c’est connu avant la sortie.

👉 Généralement, on veut prédire les revenus (box office, global sales).

🎯 Colonnes qualitatives (liées à la réception critique)

IMDBRating → prédire la note IMDb.

RottenTomatoesScore → prédire le score critique.

NumVotesIMDb / NumVotesRT → prédire la popularité (nombre de votes).

👉 Ça peut devenir un problème de régression (prédire la note) ou classification (ex: succès = rating > 7).