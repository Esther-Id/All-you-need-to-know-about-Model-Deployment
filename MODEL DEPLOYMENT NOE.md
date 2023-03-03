# Model Deployment

<img src="ML1.jpg">

__Environments:__
- There are three different environments.

__Development__ <br>
- where you'll do all of your code updates,Without affecting  what users currently see when they open the website,
- To see how new features will work and to try out improvements.

__Stage__<br>
- Think of the stage environment as the place you do the last checks and you polish things up.It is very similar to the production environment.
- Its able to give them a demo of how things work and look and  to give you any feedback


__Production__<br>

- ‘production’ or ‘production environment’ -is for making your project live.
- It is the setting where software and other products are actually put into operation for their intended uses by end users.<br>
*Of all the environments, this one is the most important*


###### What is Model Deployment?
- The concept of deployment in data science refers to the application of a model for prediction using new data,making a prediction of new data available to users or other systems.
-  To integrate a machine learning model into an existing production environment where it can take in an input and return an output.
-  You need to provide an user interface for customersto understand and utilize your machine learning model's algorith.To achieve this, you need to deploy the model on the web.

Involves the __whole ML Pipeline__ :Data collection[EDA],feature engineering,Feature selection,ML model algorithm,deployment,monitoring &recalibration
    

### __ML system architecture__<br>
in order to make your deployment process easier:
    

__Modularity:__<br>
-the code used in preprocessing/feature engineering should be arranged in comprehensive pipelines.

__Reproducibility:__<br>
the output of each component must be replicable for any version in time.

__Portability:__<br>
this refers to the ability of your software to be transferred from one machine or system to another.

__Scalability:__<br>
the model must be serveable to a large number of customers with minimal response time.

__Extensibility:__<br>
it should be easy to modify for future tasks

__Testing:__<br> 
the ability to test variation between model versions.

__Automation:__<br>
eliminating manual steps wherever possible to reduce error chances.

### Different Modes of Model Deployment

__One-off__
- Sometimes a model is only needed once or periodically. In this case, the __model can simply be trained ad-hoc when it’s needed and pushed to production until it deteriorates enough to need some fixing.__

__Batch__<br>
- Batch training allows you to constantly have an up-to-date version of your model. It is a scalable method that __takes a subsample of data at a time,__ eliminating the need to use the full data set for each update. This is __good if you use the model on a consistent basis, but don’t necessarily require the predictions in real-time__


__Real-time__
- In some cases you’ll want a prediction in real-time, for example, to determine if a transaction is fraudulent or not. This is possible by using online machine learning models, like linear regression using stochastic gradient descent.

Apart from this, deployment can also be Near Real Time or Edge.

__Machine Learning Model Deployment Patterns<br>__
- Batch
- Near Real time
- Real Time
- Edge computing

### Methods and Techniques of Model Deployment

Platform as a Service (PaaS)   __||__    or Infrastructure as a Service (IaaS).

__||__    SaaS (Software as a Service),

➔ PaaS: hardware and software tools available over the internet.<br>

➔ IaaS: cloud-based services, pay-as-you-go for services such as storage, networking, and virtualization.<br>

➔ SaaS: software that’s available via a third-party over the internet.

- A PaaS can be great for prototyping and businesses with lower traffic
- Eventually, once the business grows and/or traffic increases, you’re going to need to embrace more complexity with IaaS.__AWS, Google, Microsoft__
