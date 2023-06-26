##  An analysis of deaths in Los Angeles' deadliest year
#### Short description of what you aimed to accomplish
I sought to find out who the victims of the 1992 LA Riots are and how and where they died.

#### Short description of your findings
Of the 36 riot-related homicides, I found that 23 remain unsolved. Most victims were Black or Latino, and the leading cause of death was homicide. 

#### Summary of the data collection process, with links
I searched for riot victim data, which I found quite easily on Kaggle. Link here: https://www.kaggle.com/datasets/thoolihan/los-angeles-1992-riot-deaths-from-la-times. I then analyzed the data using pandas in Jupyter Notebook, and visualized my findings using Datawrapper.

#### Overview of the data analysis process
Because the dataset was very short and simple, I did not have much trouble during data analysis. It was easy to look at in Jupyter Notebook, but the dataset could have easily been analyzed using Google Sheets.

#### A section about what new skills, approaches, etc you used, or where you grew the most during the project: 
I learned how to use Folium in Jupyter Notebook to produce a map with the areas in which the deaths occurred. I also learned how to switch the longitude and latitude values by writing the code:  
longitude = death['lat'].values and latitude = death['lon'].values

#### A section about things you tried to do or wanted to do but did not have the skills/time (but if you have more time you might do)
I definitely wanted to go further into analyzing the unsolved cases, i.e. where most unsolved cases occurred, if there are patterns in the unsolved cases. I also feel like I would have been able to find a more compelling angle in the dataset if I had more time. 
