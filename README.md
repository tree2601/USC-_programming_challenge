USC Summer 2022 Data Challenge 
Xiaoshu Luo 9541629716

Summary of the results: 

By 2022/6/5, most of the latest 10 news articles (8 out of 10) show slightly positive attitudes but since none of them exceeds 0.1, they are approximately considered neutral. Taking the remaining two articles with obvious negative attitudes into account,the news articles about Mozambique is overall a little critical. Also, the subjectivity of all of these articles are relatively high, suggesting they are likely to be biased. 


Python code instructions:

The script is run on google colab.
The json file is in index-text format as it is concise and includes the essential information for this analysis. 
The library used for sentiment analysis is textblob, which is popular for NLP analysis. 
crawl() is the function used to scrape html info from https://www.aljazeera.com/where/mozambique/.
parse() is the function used to extract the urls for the latest urls from the website https://www.aljazeera.com/where/mozambique/. 
collect_and_save_to_json() is the function used to capture the information from urls for the latest 10 news article in json format,save them , and extract all the text information from the 10 latest news articles.
sentiment_analysis() is the function used to calculate the sentiment for each article. 
plot() is the function used to plot two bar graphs using the sentiment and subjectivity result from the last function. 
main() is the function to execute all the functions in order and produce the result. 

To reproduce the results, simply run the ipynb script on google colab and that will give the same plots. Since it is run on google colab, the path variable may need to be changed so that the script can mount on google drive correctly and export the json file. 

The total time to run the code is about 6.8 seconds.










