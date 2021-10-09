
# Machine Learning Workflow


There are five core tasks in the common ML workflow:



![enter image description here](https://cdn-images-1.medium.com/max/1600/1*KzmIUYPmxgEHhXX7SlbP4w.jpeg)

## 1. Get Data
The first step in the Machine Learning process is getting data.

This process depends on your project and data type. For example, are you planning to collect real-time data from an IoT system or static data from an existing database?

You can also use data from internet repositories sites such as Kaggle and others.

## 2. Clean, Prepare & Manipulate Data
Real-world data often has unorganized, missing, or noisy elements. Therefore, for Machine Learning success, after we chose our data, we need to clean, prepare, and manipulate the data.

This process is a critical step, and people typically spend up to 80% of their time in this stage. Having a clean data set helps with your model’s accuracy down the road.

After getting the data to a state you like, you need to convert the data sets into valid formats for your chosen ML platform. For example, you may need to translate the data into a .CSV file and upload to AWS S3.

Finally, you split your data into training and test data sets. The training set is used to train the model in the next step, while the test data is used to validate the model in the fourth step. The typical default is a 70/30 split between training and test sets.

## 3. Train Model
This step is where the magic happens! The data set connects to an algorithm, and the algorithm leverages sophisticated mathematical modeling to learn and develop predictions.

These algorithms commonly fall into one of three categories:

Binary – Classify into two categories
Classification – Classify into many categories
Regression – Predict a numeric
## 4. Test Model
Now, it’s time to validate your trained model. Using the test data from Step 3, we check the model’s accuracy.

If the results are not satisfactory, you need to improve and retrain your ML model (Step 5).

## 5. Improve
Practice makes perfect! Here are a few things you can do to refine your model and improve accuracy:

Review your model’s results with your business stakeholders. Are there other data elements worth adding to your model to make it more accurate?
Reconsider your algorithm choice. Within each class of algorithm, there are dozens of algorithm choices. A different algorithm may perform better for you
Adjust the parameters of your chosen algorithm to improve performance. Sometimes small adjustments have a significant impact.
These are just high-level steps – ML is as complicated as you choose! That said, by understanding the basic process of developing ML models, you gain a solid foundation for further learning.


[reference : https://centricconsulting.com](https://centricconsulting.com/blog/machine-learning-a-quick-introduction-and-five-core-steps/)


