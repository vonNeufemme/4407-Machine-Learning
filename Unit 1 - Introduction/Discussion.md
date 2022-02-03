## the difference between supervised learning and unsupervised learning

In essence, the machine learning is all about manipulating data, and reinterpreting the data in order to identify certain patterns and trends hidden in the data, and to draw insights from there. Although not all, there are largely two approaches to machine learning which are detailed right below. 

<br>

1) Supervised Learning (SL)

The goal of supervised learning is "predicting" the values of certain features, and here the word 'predicting' matters. When we say 'predict', we assume and agree that certain things are expected to have certain value. Let's take an example. In the realm of Machine Learning, Boston housing price prediction makes a good chapter about supervised learning, so let's say we want to buy a house and we are browsing properties in the market. Every house has a different price but we deem that a certain price is acceptable for a specific house considering its unique conditions -- number of bedrooms and bathrooms, area, location, district crime rate, neighbourhood safety, distance to facilities (school, hospital, etc). The reason we can predict and accept certain value range is because certain values like house prices fall well into a deterministic value range. 

So how does it work? It works by providing the SL algorithm a pair of input data and prediction labels. The algorithm will adjust the wegiths for the algorithm so all input data and labels are fitted to the equation (this process is called training). Based on this equation and weights calculated through the model training, the model will be able to calculate (predict) the value for a given unknown input after the training. 

<img src="https://github.com/deep-woods/UNI-2022-4407-12-Machine-Learning/blob/main/images/Unit_1_Supervised_learning__linear_regression.png" />

<br>

2) Unsupervised Learning (UL)

Unlike SL, UL does not attempt to 'predict' values as there is no fixed answer. It, rather, tries to identify the patterns in the dataset. How is it different from SL then? The most noteworthy technical difference is that we do not feed known labels for a given input data when we train an unsupervised model. It is trained without the supervision of correct answers, and we just manipulate the data to draw some insights from it.

A good example of SL application is customer segmentation. Considering certain features of customers (annual income and their spending habits, for instance), we can group them into different clusters to identify customers' shopping inclinations and tendencies. As you can see in the graph below, the customers are divided into 5 different clusters. We we are not expecting lower income groups to spend less and higher income groups to spend more (supervised learning for deterministic/predictable answers). We are looking to find out what are their spending inclinations (no fixed answer, just looking for patterns).

<img src="https://github.com/deep-woods/UNI-2022-4407-12-Machine-Learning/blob/main/images/Unit_1_Unsupervised_learning__clustering.png" />

<br>

### References

  - IBM (n.d) What is Supervised Learning? https://www.ibm.com/cloud/learn/supervised-learning
  - IBM (n.d) What is Unsupervised Learning? https://www.ibm.com/cloud/learn/unsupervised-learning
