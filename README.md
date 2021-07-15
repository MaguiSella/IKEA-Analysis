# IKEA Analysis
 Analysis of possible new locations for IKEA stores in Sweden

IKEA is a Swedish furniture firm that is currently present in 18 Swedish municipalities: Borlänge, Gävle, Göteborg, Haparanda, Helsingborg, Jönköping, Kalmar, Karlstad, Linköping, Malmö, Stockholm, Sundsvall, Uddevalla, Umeå, Uppsala, Västerås, Älmhult, and Örebro. Since the firm is analyzing the possibility to expand, an analysis was performed to find the next municipalities for this company to open a store. 
With this purpose in mind a dataset comprising information about different Swedish municipalities was analyzed. The dataset included information regarding the population of the municipalities, whether it had infrastructure available, the productivity and sales index of the municipalities, among others. This information was condensed by means of principal component analysis in such a way that at least 95% of the variance was explained by the principal components selected for the analysis. This resulted in three principal components, which were then used to cluster the municipalities. 
By applying the elbow method 3 was found to be the optimal number of clusters, which resulted in Stockholm being isolated in its own cluster, and having the remaining municipalities divided among small and medium ones. When analyzing where the already existing IKEA stores were located, it could be seen that the variables that were the most correlated to having an IKEA store were sales index, revenue, population, and employees, as can be seen in the next figure.

![image](https://user-images.githubusercontent.com/44349963/125710091-fc2720f6-e057-49a3-a645-89fc924e4028.png)

With this information, the analysis proceeded by means of mapping the municipalities without IKEA that scored the most in these variables. The first 5 candidates were: Norrköping, Huddinge, Falkenberg, Järfälla, Lund, Täby, Nacka, Mölndal and Borås. When setting them all on a map, as can be seen in the next figure, three of them are in close distance of Stockholm, Huddinge, Täby and Järfälla. Since they are withing short distance of a major IKEA setting, we believe it would not be greatly beneficial to set up a shop there, since it is likely that the possible customers living in those areas are already shopping at Stockholm’s IKEA stores. 

![image](https://user-images.githubusercontent.com/44349963/125710050-f0a6297d-981b-465a-bb6a-eaf58a04cf1c.png)

The locations that are further away from IKEA stores and that have good ratings for all the relevant variables are Norrköping, Falkenberg and Borås. The first two of them were the best suited options without regard to closeness to other IKEA stores. Thus, our recommendation would be to further analyze the possibility of opening a new store in one of these three locations.
 
