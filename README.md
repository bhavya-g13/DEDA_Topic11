[<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/banner.png" width="888" alt="Visit QuantNet">](http://quantlet.de/)

## [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/qloqo.png" alt="Visit QuantNet">](http://quantlet.de/) **RedditWSBSentiment** [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/QN2.png" width="60" alt="Visit QuantNet 2.0">](http://quantlet.de/)

```yaml

Name of QuantLet: RedditWSBSentiment

Published in: DEDA Class SoSe2023

Description: Optimizing investment portfolios by analyzing the risk and return characteristics of different assets. By employing the Markowitz model, we provide a quantitative approach to portfolio diversification and asset allocation, aiming to maximize returns while minimizing risk.

Keywords: Portfolio management, Markowitz model, asset allocation, diversification, risk-return analysis, investment optimization

Author: Ruchir Dhiman, Bhavya Goyal, Jonas Saleh

Submitted: Tuesday, 11 of July 2023 by Bhavya Goyal

```

# Cross Correlation of the Sentiment in r/wallstreetbets and GME and AMC stocks during the Gamestop short squeeze

![Proportion of Positives and Negatives](./images/n_posts_comments.png)

## Objective
Analyze the potential correlation between GME and AMC stock with Reddit posts and comments using Sentiment and Cross
Correlation Analysis


## Get Started
In order to reproduce the whole repo, make sure to comply with Reddit API Requirements and have your client id,
client secret and user name on a `config.yml` file.
In our case, it is called `config-personal.yml` and it is in the parent directory. Create a ```data``` directory as well.

The posts data can be found on this [Kaggle Repository](https://www.kaggle.com/datasets/gpreda/reddit-wallstreetsbets-posts?resource=download).

## Reproduction
To reproduce the main findings and get the processed data, please refer to ```src``` folder and run the files sequentially.

For the frequency plots and checks on stationarity for the stock data, please refer to the ```notebooks``` folder.
