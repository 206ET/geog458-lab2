# GEOG 458 Lab 2: Web Data Collection and Visulization

## Topic

The topic I chose for this lab is **housing prices**, with a geographic comparison between **Seattle, WA** and **Bellevue, WA**. I was interested in examining how housing is discussed online in these two nearby cities and whether any themes differ between them. This was very interesting to me as someone who wants to live in Seattle for the foreseeable future and God willing raise a family here.


Using the provided lab template from the lab instruction github, `youtube.ipynb` notebook, I collected YouTube video data for two separate searches:
- **Seattle housing**
- **Bellevue housing**

For each location, I collected **20 video results**, extracted the text descriptions, and saved the results as CSV files. These datasets are stored in the `assets/` folder in my repository folder for this Lab.

## Why I Chose This Comparison

Seattle and Bellevue are geographically close but differ in terms of development patterns, population density, and housing markets (both are pretty expensive). Seattle is often talked about as a very dense, high cost urban environment, while Bellevue is frequently framed as a high cost tech-oriented city. Comparing these two locations allows for a clearer understanding of how public discussion around housing may vary even within somewhat the same region.

## Word Cloud Comparison

The following word clouds were generated from the YouTube videos that I collected for each city. In the word cloud it visualized the most frequently occurring terms from the videos related to the housing searches about Seattle & Bellevue.

### Seattle Word Cloud

![](img/wordcloud-1.png)

### Bellevue Word Cloud

![](img/wordcloud-2.png)



## Similarities and Differences

Both word clouds contain common housing-related terms, terms such as affordability, housing availability, and living conditions. This lets us assume that these things are pretty big concerns across both Seattle and Bellevue. This indicates that housing is a significant issue throughout the broader Seattle area. However, there are noticeable differences in word emphasis between the two word clouds. Certain terms appear more prominently in one city than the other, suggesting differences in how housing is discussed depending on the location. These differences may reflect variations in audience focus, housing types, or local economic conditions.

## Possible Reasons for Observed Patterns

The observed patterns may be influenced by differences in city identity and housing markets. Seattle-related videos may emphasize urban issues such as density or cost of living, while Bellevue-related videos may focus more on development, suburban living, or real estate investment. Additionally, YouTube’s recommendation algorithm and content creators’ perspectives may affect which themes are emphasized.

## How This Research Could Be Improved

This research could be improved by collecting maybe an even larger number of videos for each location or by including additional cities in the comparison. Analyzing comments or transcripts instead of only descriptions could also provide deeper and better insight. 

## Observations and Takeaways

One key takeaway from this comparison is that while Seattle and Bellevue share many housing-related concerns, the way housing is discussed online varies by location. This highlights how geographic context influences public conversation, even within closely connected cities. Bellevue had more mentions of words that were negative that conveyed high prices in the sense of describing the housing market over there compared to Seattle.

## Data Downloads

The datasets used in this analysis can be downloaded below:

- [Download Seattle housing data](assets/search-result-1.csv)
- [Download Bellevue housing data](assets/search-result-2.csv)
