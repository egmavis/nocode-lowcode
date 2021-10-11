# No Code/Low Code NLP
#### Analysis of Jane Austen's *Emma* and Charlotte Bronte's *Jane Eyre*

### Initial exploration of the two novels completed in Google CoLab
[EDA in Google Colab Notebook](https://github.com/egmavis/nocode-lowcode/blob/main/EDA_text.ipynb)

### AWS Quicksight Analysis
Used AWS low-code tools to generate quick, sophisticated data visualization charts. 

There are some limitations to these visualizations, mostly due to the fact that stop-words are still included in the data frames used. In the future more effective cleaning of the text data can be done in order to have a more accurate analysis. For now, we can come to some surface level conclusions.

The pie charts show many occurances of words like "the" and "to," words that are typically ignored. But they also do show that "her" and "she" are used frequently in both novels, which indicates they are both feminine-focused and have perhaps mainly female characters.

![Emma Pie Chart](https://user-images.githubusercontent.com/69800932/136804279-228ea13b-18e9-4413-82f1-998f1efa173b.png)
![Jane Eyre pie chart](https://user-images.githubusercontent.com/69800932/136804289-c9a68607-2327-4a8a-9e95-013793b1fa2d.png)

The frequency bar charts show more of a breakdown in words. Some key words in *Emma* that show up are "great," "fairfax," "young," "woman," "randalls," and "world." These top words can give us an overview of the tone, which in this case is quite light and positive. Going deeper into the frequency chart we see words like "dear," "himself," "feel," "john," and "together." The tone seems to get a bit more serious and we have the introduction of masculinity.

![Emma bar chart 6Kmax](https://user-images.githubusercontent.com/69800932/136804284-a0cdf368-f998-4f12-8377-4e64662cfca9.png)
![Emma bar chart 1.2K max](https://user-images.githubusercontent.com/69800932/136804281-93c84782-fea6-4945-8419-490d65ef04d6.png)

Now looking at the top-level words occurring in *Jane Eyre*, we see "you," "his," "never," "left," "found," "man," and "far." Already we can see a stark difference in theme and even tone as compared to *Emma*. Masculinity is much more prevelant and the tone is a bit darker. Going deeper into the frequency chart we see words like "miss," "thought," "night," "both," "young," "give," and "perhaps." There is now a a dose of female and the tone has changed to something a little more romantic.

![Jane Eyre bar chart 6K max](https://user-images.githubusercontent.com/69800932/136804288-7113466f-0d2d-4546-969f-eaf6c8324492.png)
![Jane Eyre bar chart 1.2K max](https://user-images.githubusercontent.com/69800932/136804286-3a5bec1a-085c-4ff7-86d8-f160a8021c0f.png)

Based on this very surface-level analysis, we can conclude that both novels revolve around the relations between men and women, but *Emma* stays a bit lighter in tone whereas *Jane Eyre* is darker and more serious.
