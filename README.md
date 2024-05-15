# 6950_final_project
## Introduction
Hello, everyone. My final project is called Elephant Migration Corridor Planner. This is a web application that combines a cloud-based database with a route optimization model. Before we get to the program.

## Model Framework
The model has five major components: data collecting, Model building, data storage, map generating, and web interaction.

In the data collection section, I will collect various types of data related to elephant migration, including elevation, forest coverage, length of water sources, and so on., and I use ArcGIS to integrate those data into a standard integration data format. Then I will use Python to transform the obtained data into Graph format for Network Route Analysis, and then I can use Dijkstra's algorithm to calculate the optimal migration route. The results of the calculations will be imported into Bigquery in the form of a data table, together with the organized base data.
With the data warehouse, we can visualize the data through carto and present it to the public through web pages.

## Data Collecting
The Data we use here is collected from the National Geomatics Center of China. The data includes the Digital Elevation Model (DEM), City Border, Forest Resources, River System, and existing conservation areas of Yunnan Province, China.

https://www.gscloud.cn/#page1/1

## Data Storage & Visualization
For the Data Storage, I transformed the result data into a CSV file and stored the data in Google Cloud.

With the Cloud Database, we can use Carto to visualize the spatial data and present it to the public with HTML web page.

## Final Project
**Web Page:**

https://zhaiyuanhao.github.io/6950_final_project/final_project_test.html

**Detailed Technical Documents:**

https://github.com/zhaiyuanhao/6950_final_project/blob/0f07bb9daab2e1a8bbaa3535cbce3d9cb9f5d610/MUSA%206950%20Final%20Project_Asian%20Elephants%20Migration%20Route%20Planner_Yuanhao%20Zhai.pdf

**Presentation Video:**

https://youtu.be/5rEfWzYwrOc
