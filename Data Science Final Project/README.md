# DATA SCIENCE PROJECT
# SpaceX Falcon 9 first stage Landing Prediction

<p>
we predicted if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch. In this project, we will collect and make sure the data is in the correct format from an API. The following is an example of a successful and launch.
</p>

![giphy](https://user-images.githubusercontent.com/53977573/173599312-49e7ca1d-6f3b-427c-bc19-10d9a490f5b6.gif)

## Collecting the data
<p>
In this task, we will make a get request to the SpaceX API. We will also do some basic data wrangling and formating.
</p>

<ul>
<li>Request to the SpaceX API</li>
<li>Clean the requested data</li>
<li>Replacing the Missing values</li>
</ul>

## Web Scraping
<p>
In this task, we will  performe web scraping to collect Falcon 9 historical launch records from a Wikipedia page titled List of Falcon 9 and Falcon Heavy launches
</p>
https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches
<p>
Web scrap Falcon 9 launch records with BeautifulSoup:
<ul>
<li>Extract a Falcon 9 launch records HTML table from Wikipedia</li>
<li>Parse the table and convert it into a Pandas data frame</li>
</ul>
</p>

## Data Wrangling
## Machine Learning Prediction
<p>
Performed  exploratory Data Analysis and determined Training Labels
</p>
<ul>
<li> created a column for the class</li>
<li> Standardized the data</li>
<li> Split into training data and test data</li>
</ul>
<p>
Found the best Hyperparameter for SVM, Classification Trees and Logistic Regression
</p>
<ul>
<li>Found the method to performs best using test data</li>
</ul>
