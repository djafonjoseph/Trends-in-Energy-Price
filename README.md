# Introduction

Using machine learning algorithms, this project analyzes some common trends between the prices of certain energy materials. Thus, unlike traditional approaches based in particular on autoregressive processes or moving averages, we use supervised learning methods to predict oil price changes based on the prices of other energy materials such as gas, cobalt, uranium, coal, bauxite and aluminum. More specifically, we use Ridge regression, Lasso, which allows us to deal with multilinearity problems, but also Random Forest, which manages to capture more complex and non-linear relationships. We use data from 2011 to October 2023. This choice is explained Our data come from the Federal Reserve site, apart from those on cobalt that come from the site. "Investment.com".Our results are of several kinds.

# Main results and implications

First, regarding the methods used, the Ridge and Lasso offer similar results, with relatively low turning parameters indicating a similarity with a linear model without constraints. Nevertheless, we see that these two models fail to capture certain fluctuations in oil prices over certain periods. On the contrary, the Random Forest manages to make better predictions of oil prices due to its ability to detect possible more complex and non-linear relationships. Mean square error is the lowest of these three models for both the training set and the test set.

Secondly, our results show more complementarity than substitutability between fossil and more or less renewable energy prices. Fossil fuel prices such as coal and oil continue to experience the highest average price levels. This shows that there is still a strong demand for fossil fuels despite the numerous incentives, notably from public authorities but also from shareholders, for a greener economy. These results also reflect cost reports calling for more investment to reduce the exploitation and use of more renewable energy.

# Limits and further request

Nevertheless, the scope of our results remains limited by the nature of our specification and estimation method. They therefore remain to be confirmed and tested on broader data, with other methods such as those based on neural systems such as the Recursive Neurone network (RNN) or more conventional models of temporal analysis such as ARMA, MGARCH, ARDL, etc.

# Authors
DJAFON Kokouvi Joseph
RAZAFIMANANTENA Iriantsoa
KAPO Din
