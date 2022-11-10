# Gathering-and-Analysing-WeRateDogs-Tweets
This project showcases data gathering and wrangling skills .
It is carried out using three different datasets concerning WeRateDogs twitter page.

One of the datasets which is a tsv file is gathered directly from the web using requests library.
The second is loaded from the local computer, while the third is scraped directly from twitter using twitter APIs.
It is saved as a csv file and then read into a pandas data frame.

The data frames were assessed individually and cleaned. They were then merged into one dataframe for the analysis process.

Findngs show that:
<ol>
<li>A dog’s breed can be predicted correctly by looking at its image. 
About 85% of the dog breeds were correctly predicted using their image(s)</li>
<li>The dogs in the doggo_puppo stage are clearly much loved as they gathered the highest favorite counts and the highest rating.
Their favorite counts was almost double the favorite counts of the second highest dog stage which is puppo.</li>
<li>Dogs in the pupper stage appear to be least loved. They had the least favorite counts as well as the least rating.</li>
</ol>
