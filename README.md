# Recommendations with IBM

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Dataset](#dataset)
4. [File Descriptions](#files)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
Beyond the Anaconda distribution of Python, there are no external libraries necessary to run this code.

## Project Motivation <a name="motivation"></a>

Recommender systems are one of the most successful and widespread applications of machine learning technologies in business. They also play an essential role in helping users find products and content they care about.

Even though I've known the impact a good recommendation system can have I've never really understood how companies like Spotify, Amazon, and Netflix could provide such good recommendations. No better way to learn than to build it myself (simplified version).

The recommendation system I'll be creating will be able to suggest articles on the [IBM Watson studio platform](https://dataplatform.cloud.ibm.com/) to users.

Below is an image that illustrates how the recommendations could be presented to the user.

![](assets/Recommendations_with_IBM.png)

## Dataset <a name="dataset"></a>
In order to determine which articles to recommend to each user, I'll be performing a study of the following datasets:

* `/data/user-item-interactions` - This set contains user interactions.
* `/data/articles_community` - This set contains details about the articles.

## File Descriptions <a name="files"></a>
Available files in this repository:
* `Recommendations_with_IBM.ipynb` - code for the recommendation system.
* `Recommendations_with_IBM.html` - same as above but in HTML-format.

The remaining files are for tests provided by Udacity.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
I would like to thank IBM for the datasets and Udacity for an excellent project.