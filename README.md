# CMPT310-VGSales-Neural-Network
A project for CMPT310.

The data is from: https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings. 

In this project, the model attempts to predict the sales of a game based on its ratings by both users and critics on Metacritic. While Metacritic scores are often flawed, there may be a correlation between a game's perceived quality and how much it sells.

First, the data is cleaned, removing rows with empty elements, and unnecessary columns. Then, the critic and user scores are adjusted to be on the same scale. Lastly for data processing, X and Y are obtained by selecting only the critic/user scores and global sales columns. Additionally, it should be noted that games that sold over 50 million copies are ignored, as they are outliers and are not representative of the overall sample space.

The data is split into three test sets, train, dev, and test. Initially the data is split into train and test, then, the data is split again to obtain a dev set alongside the true train set. Ultimately, the split ratio comes out to be 0.6, 0.2, 0.2 for train, test, and dev respectively.

****************************
This project was completed for CMPT310 - Introduction to Artificial Intelligence on April 18th, 2023 at Simon Fraser University.
