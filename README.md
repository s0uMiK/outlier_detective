# outlier_detective

# Introduction

Recently New York Times carried an Article about Chinese Hackers forcing a black out in Mumbai during the Ladakh standoff 
Link - https://www.nytimes.com/2021/02/28/us/politics/china-india-hacking-electricity.html

## Public Utilities and Vulnerability Industrial Automation Systems 

Public Utilities like Water , Electricity and Industries depend on automation system that are vulnerable. Most of these data systems use older technologies and proprietary protocols. These protocols through were good for a standalone system have failed in a heavily interconnected world. The systems are therefore are at the mercy of hackers. A system needs to be developed to enable these older system that cannot have embedded security architecture to be protected. 

## Features of UEBA Solution

An effective UEBA the solution has at least the following properties:  
1. Effective data collection and data representation layer 
2. Correlation of entities identifiers to users and user accounts to users 
3. Abnormal behaviour detection 
4. Specific threat detection 
5. Discovery of core systems and privileged users as well as peer groups or communities 
6. Linking together of multiple detection results into a coherent threat view across enterprise Suspicious Entity and User Detection Analytics 
In addition it is essential to have capabilities to add new analytics and reconfigure existing ones: play (by developing new analytics) and plug (for automated results) framework

## Solution Approach – Entity Behavior Analysis (EBA) Workbench

The Solution is based upon a paper published in KICS

![Untitled drawing (1)](https://user-images.githubusercontent.com/46192583/153341783-3778ffde-8f27-4f2f-a74f-d9b7c57494de.jpg)

-> To design a system that would ingest time series data from systems and even directly from devices directly 
-> Behavioral analytics workbench automates the detection of risky behaviors inside	an organization and boosts the power of security teams by accelerating alert prioritization, incident investigation and threat-hunting efforts.
-> It ingests time series data logs from the infrastructure to model Behavior 
-> To use Deep Learning Algorithms, Recurrent neural networks, Deep neural networks, restricted Boltzmann machines, Deep belief networks, Convolutional neural networks , LSTM and Deep autoencoders.  
-> Out of the box tools are directed towards a more matured market that uses latest IoT devices my workbench will allow users to manipulate the algorithms to suit their needs.
-> The entire workbench would work of a powerful Laptop and not on expensive server hardware , this will allow cybersecurity experts to use the environment in a remote location

## Aim of the project

The aim of the project is to develop a platform using machine learning techniques that takes a test log file as input, learns the basic format and should be able to indicate that some logs are anomalous. Some of the objectives are: 
1. Process incoming logs in CEF, syslog, key-value format, API. 
2. To employ unsupervised ML and detect outliers in log stream. 
3. Studying adversary behaviour as per MITRE framework and applying them to detect anomalous user and entity behaviour. 
4. To act as feed forward for other detection and response platform

## Block Diagram

![Untitled drawing](https://user-images.githubusercontent.com/46192583/153341600-8edf75ac-3da4-4df1-82e7-702b81ed2143.jpg)

![Untitled drawing (2)](https://user-images.githubusercontent.com/46192583/153342952-dcf32d6b-2e6b-44f3-b70b-433ea160eded.jpg)

## Libraries Used

● Pandas 
● Numpy
● Tensorflow
● Scikit Learn 
● Pyod 
● Pycef
● Drain
● Joblib
● Python 3.7
● ElasticSearch
● Kibana
● Jupyter Notebook

## Conclusion

1. Demonstrated how to detect outliers in the log streams of different log formats.
2. Cyber security analysts can use this algorithm for finding irregularities in the different log streams.
3. Found out different methods to parse different formats of log files. 
4. Various visualizations can be used in kibana lens to show the behaviour of the log streams.

## Future Scope 

1. This algorithm can be used in the distribution systems in power plants, to monitor log activity of the PLCs inthe power distribution system. Certain custom libraries are required to be written for brand specific PLCs
2. With the help of some javascript libraries, this algorithm can be used in multi-user environments. 

## Output

![Untitled drawing (3)](https://user-images.githubusercontent.com/46192583/153343085-b89a1c7b-8888-49d1-ae27-71243692037e.jpg)

