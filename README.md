<html>
<head>
<style>
.button {

.button3 {background-color: #f44336;}

</style>
</head>
<body>

## Movie Recommendation for Social Graphs

The data used is from GroupLens and can be downloaded [here](https://grouplens.org/datasets/movielens/latest/). Due to the huge amount of data the small dataset is used. The data consist of 4 csv files where 3 of them is used; movies.csv consists all the movies used, ratings.csv consists of all ratings given by users for the different movies, and tags.csv consists of tags a user have given to the movies. In total that gives 9742 movies, 100,838 ratings, 3683 tags and 600 users **insert correct number**.

To get more information about the data and how the webpage is created see the [explainer notebook](https://nbviewer.jupyter.org). **(Put the explainer notebook up here)**

## Sentiment analysis

All the movies was divided into genres. All movies have a plot, where the sentiment for the plot is found. The distribution of plot sentiments can be seen by choosing the corresponding button.

<button3 onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_(no genres listed).png'">no genres listed</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_Action.png'">Action</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_Adventure.png'">Adventure</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_Animation.png'">Animation</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_Children.png'">Children</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_Comedy.png'">Comedy</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_Crime.png'">Crime</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_Documentary.png'">Documentary</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_Drama.png'">Drama</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_Fantasy.png'">Fantasy</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_Film-Noir.png'">Film-Noir</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_Horror.png'">Horror</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_IMAX.png'">IMAX</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_Musical.png'">Musical</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_Mystery.png'">Mystery</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_Romance.png'">Romance</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_Sci-Fi.png'">Sci-Fi</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_Thriller.png'">Thriller</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_War.png'">War</button>
<button onclick="document.getElementById('sentiment_plot').src='images/plot_sentiment_Western.png'">Western</button>

<img id="sentiment_plot" src="images/plot_sentiment_(no genres listed).png" style="width:600px">




## Wordclouds

<img src="images/neg_plot.png" alt="hi" class="inline"/>

<img src="images/pos_plot.png" alt="hi" class="inline"/>


## Usefull informations
Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
