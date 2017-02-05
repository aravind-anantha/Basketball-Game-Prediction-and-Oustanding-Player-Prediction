# NBA game outcome prediction and outstanding player detection

The plausibility of predicting sporting events’, simulating games, and estimating the performances of athletes is naturally attractive to businesses, coaches, and researchers. Especially, that plausibility for such major and professional sport league as National Basketball Association (NBA) has influences and fame across countries all around the world. For this milestone of the project, the main objective is to report current progress and experiments’ results from using various Machine Learning methods.

There are 34 features for our NBA dataset. We use data beginning from the 1980 season since that is when 3 pointers were first introduced. The input is a team feature vector containing the 34 features for all NBA teams for several seasons. Each data point is the performance of each team in a season. Various approaches for feature selections (BIC, PCA, and stepAIC) would be applied along with linear regression model and SVM Regression for team win ratio of per year prediction. Outstanding players are predicted based on the various attributes such as rebounds, steals, three points etc. We are making use of multivariate outliers library in R to perform outlier detection.

### Instructions to run the code:
* All the code is written in R
* Please install the required packages, for example: mvoutliers package is required to run outlier detection algorithms.
* Please set the working directory to the location of the data file in your local machine
* Run the script

