# Mobile-Price-Range-Prediction-Capstone-Project
In this era of technology there are various electronic gadgets that are created or invented by humans.
About two decades ago the craze of technology was not that much but from last few years this craze
is at its peak. Now a days people are mad about mobile phones and other gadgets. Mobiles are now
every one's first choice gadget, either an elderly person or a younger one. Every person’s hand is
equipped with latest mobile models and everyone has its own reason to have this magic gadget in his
hands.

So, because of it we came across this project. In this problem we have to predict the price range of
mobile phones according to functions of mobiles. The dataset that provided here consists information
of different features of mobiles. There are features like Wi-Fi, Bluetooth, network connectivity like 3G
or 4G support, screen width, screen height, weight of mobiles, RAM, internal memory and various
others. Therefore, depending on these features, the price range of mobiles will be decided. And
depending on that we have to predict the range of price.

Now its time to take a look at implementation of code. So, in first few steps we checked for null values
in the dataset but fortunately our dataset did not have any type of null values. Then we searched for
outliers and we came to know that there are negligible number of outliers that we can ignore.
Then we drew some insights from the dataset. The insights like, the relation between RAM of mobile
and price range is much positive also the relation between Internal Memory and price range is also
much positive. Positive in the sense that when we increase the RAM or Internal Memory of particular
mobile then that mobile will be placed in high price range and vice-versa.

After that we divided the dataset into train and test groups. Then we applied some Machine Learning
models like Decision Trees, KNN and Random Forest etc. to train the training dataset and then we
tested that results on test set. And evaluated these models with some evaluation metrics like printed
their confusion matrix also accuracy score. Then we did Grid Search CV to find the best parameters of
Random Forest classifier algorithm. So, that’s how we pipelined our project.

Through Random Forest algorithm we have identified the price range of various mobiles. Plotted the
RAM and price range graph through which we came to know the impact of different RAM sizes on
price range. And with the help of various features, we decided to set how much price range of a
particular should be which have the particular features.
