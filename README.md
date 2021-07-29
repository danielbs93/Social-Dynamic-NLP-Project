# Social-Dynamic-NLP-Project
## Political trends in Twitter and their sources In the Israeli political Twitter feed

[Political trends in Twitter and their sources In the Israeli political Twitter feed.pdf](https://github.com/danielbs93/Social-Dynamic-NLP-Project/files/6899945/Political.trends.in.Twitter.and.their.sources.In.the.Israeli.political.Twitter.feed.pdf)


The purpose of this study is to get insights on the Israeli political twitter feed with focus on trends and influencers. Twitter is among the top three social networking sites in the world. Twitter is basically a service that allows registered members to broadcast short posts called tweets. Born in 2006, it has 330 million monthly active users 80 percent of which are mobile.

In this project we are aiming to find political influencers in the Israeli twitter feed. For obvious reasons we cannot measure the influence that some tweet has on some users directly and for that reason we are looking for the connection between users and trends. We assume that some users have the power to cause a phrase become trending, meaning that their posts is an idea that travel through the structure of the social media network. This assumption has a clear bias, an idea can reach users from different sources other than the people they interact with in twitter. For example a person can be exposed to an idea to a tweet from other social media platforms or the
mainstream media and post it on twitter “from scratch”.

### How you should approcahing the Jupyter Notebooks

First you need to have your datasets. If your desire is to scrap tweets then take a look on the TwitterCollector.ipynb to see the right way to scrap your data in order to process it into the deep learning model. The most important thing to take into your consideration is the right names of the columns in the DataFrame when you ever wish to use your own dataset into the DL model.

Next, the Jupyter Notebook is the ClassifyingModels.ipynb which constructed with 3 main category models: the naive ones, Bi-LSTM and BERT.
The naive models are used as a baseline models which includes the Perceptron, MultinomialNB and the SVM algorithms.

Last, the SocialNetworkGraph.ipynb which consists the classification of tweets trends that we have gathered and then using NetworkX Lib we have created graphs and visualize it with Gephi software.
