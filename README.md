# Data Visualization Project Proposal

## Final Presentation Link
https://youtu.be/6t2cEedb_Cs

## Data

The data I propose to visualize for my project is the TMDB Top 5000 Movies data set mostly because the dataset contains tons of information that can be visualized in the interactive portion such as movie keywords, genres, taglines and revenue/production cost split and runtime info. This is plenty of information and should lead to some interesting conclusions if visualized nicely.

Link to Original Dataset: https://www.kaggle.com/tmdb/tmdb-movie-metadata

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Is there any particular Genre that dominates the top 100 or 50 movies, are there any outlier genres in this top section?
 * Is there a corrilation between keywords for a movie, and the budget a movie requires, what keywords occur most often in the top 5000 movies?
 * Which production companies tend to produce the best movies, is there a certain production company that creates a best reutrn on investment?
 * What is the relation between popularity of a movie, and the runtime of the movie, do people really tend to prefer two-ish hour movies?
 * What is the relation between genre and budget these top movies, is there a genre that is cheap to produce and always has a good return on investment?

## Prototypes

## UPDATES

I’ve created a proof of concept visualization of this data. It's a scatter plot that shows all 5000 top movies relation between Runtime(X) in minutes and Budget(Y). We see that these movies average a runtime of around 120 minutes. All of the highest budget movies are around the average runtime. No large production studio would finance a really short or long movie, and the highest budget movies are almost exactly two hours. If I could improve this chart, I would work to fix any oclusion that is occuring with dots overlapping each other. This would hopefully provide more information to the viewer.


![TimevsRevenue](https://user-images.githubusercontent.com/44755928/134382327-76104927-3718-4496-96a1-bf448ae94763.PNG)

I have added converted the scatter plots to be transparent to prevent data occlusion. This verion also improves the X and Y axis labels. This iteration can currently be found at https://vizhub.com/T-Reiser/cf07600ad704409a96d2c251afd7b71b.

![image](https://user-images.githubusercontent.com/44755928/139132621-fa5113a2-7570-4963-9742-80b108016d24.png)

I have continued updating the top movies data visualization with a better color scheme and additional functionality. My original goal for this project, was to be able to change the display chart to show interesting correlations in the dataset. One of the most interesting aspects of this project was the fact that the orignal Kaggle set included the taglines and keywords that were part of the marketing for all of these top movies. I was originally curious about the overlap for these, however it isnt practical to sort by keywords in a scatterplot, because there is huge variation, and the most common words would grammer articles. Additionally, I was hoping to display the length of these taglines as one of the data feilds, however I found that even sorting by the length doesnt produce an enticing graphical representation. Alot of the information in the dataset is irrelivant for our vizualizations, such as original language, spoken languages, and production origin company. One of the last things I will try is to parse the production companies for each movie, and maybe display the most common across the board. 

I have also been working with the interactive menu to display different dat points based on the axis selected in the drop down menu. This is building upon the interactive menu information we learned about a couple of weeks ago. https://vizhub.com/T-Reiser/f9f8dac03e3b466eb4a0855be8474c11
![image](https://user-images.githubusercontent.com/44755928/139162343-98709205-2e90-44ca-8577-1e525f9a77e0.png)

Based on the examples worked on last week, I think that having drop down menus to select what data is displayed on the X and Y Axis in the scatterplot makes sense as an interaction for this project, specifically because of the large number of data fields selectable.

Another possible interaction I would like to implement is adding hoverable bubbles for each datapoint that would show you the movie title if that is not already displayed. That way, if there is a particular outlier, it would be easily identifyable for further research.

## Schedule of Deliverables

* Select Dataset for final project (DONE)
* Decide on primary data visualization method (DONE - I have selected a scatterplot as the primary dat visualization method)
* Refine Vizualization (1) - (DONE - Minor refinements such as ensuring the Axis titles are displaying, and making the data points semi-transparent )
* Add Axis Selector Interaction - (Work in progress, I have a template and partial examples of how to implement, and working on that now, should be done by 10/15)
* Add Hover Interaction - (TODO, I have the concept finished, and will do some research to determine how to implement, should be done by 10/20)
* Refine Vizualization (2) - (TODO, Once the main interactions are added, I want to do a final run over and add color or refine the style, should be done by 10/22)

## Sketches

Here are two sketches that show potential charts that could be made with the choosen dataset. The first shows the Budget($) Vs Revenue($) of the top grossing movies in the dataset. This would allow us to see how much money influneces the revenue a movie makes, and we could also see which movie had the best return on investment.  
The second chart is a scatterplot that shows the Revenue($) Vs Tagline length of a movie. This could provide an interesting result and allow the viewer to see if better performing movies tend to have shorter or longer tagline. We could also improve this data to color it relative to how much certain words or ideas appear in the taglines. 

![vissketch](https://user-images.githubusercontent.com/44755928/134382090-286d9e1d-d209-49a9-91f8-89454eced42a.jpg)


