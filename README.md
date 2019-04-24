# Toolwear Detection Analysis

## Introduction
In today’s world of global competition, on-time delivery and meeting tight deadlines have been a critical factor. In manufacturing and production domain efficient production lines play a very important role in meeting these tight deadlines. These can be achieved by reducing the downtime of shop floors. The efficiency of production deadlines depends on the quality of the tools and machines used. Well, without any surprise, tool wear is a significant factor for downtimes. In an automated system if a worn tool goes undetected it can cause damage to the workpiece, disrupt the entire production line and also incur a blow to one’s reputation. It has been reported that successful tool detection of tool breakage/wear can save up to 40% of production costs.

Our aim for this project is to address this problem using machine learning and study how our problem can benefit from it. Data from different sensors of a CNC machine is collected using both a worn and an unworn tool. A series of machining experiments were carried out on wax blocks in a CNC Milling machine in the System-level Manufacturing and Automation Research Testbed (SMART) at the University of Michigan. Machining data was collected from a CNC machine for variations of tool condition, feed rate, and clamping pressure from 18 different experiments. We thank Kaggle to make this dataset available.

## Acknowledgements
This data was extracted using the Rockwell Cloud Collector Agent Elastic software from a CNC milling machine in the System-level Manufacturing and Automation Research Testbed (SMART) at the University of Michigan.

## How to run this project?

To execute the code, run the following commands: (ensure the csv files are in the same folder as the code file)

Packages: [numpy , pandas , sklearn, matplotlib, seaborn]. Install it using following commands.

pip install pandas
pip install sklearn
pip install sklearn
pip install matplotlib
pip install seaborn

This project also uses Keras, using Tensorflow as backend. Please ensure that you setup specific framework as per your system requirements.
Our System Configuration.
OS: Mac 10.13.4
Language: Python 3.6.4
Backend: Tensorflow [v1.11.0]

Use following commands to setup Keras.
Packages: [keras v2.2.2]

pip install --user --upgrade tensorflow
pip install keras

After setting up environment please run pythin script using following command.

python3 ./toolweardetection.py

## Developers:
1. Bandeep Singh Dua
2. Akshay Chaudhari
3. Pranav Reddy Anumulla
4. Bhavik Patel
