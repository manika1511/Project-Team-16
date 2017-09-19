# EMERGENCY 911 ANALYSIS AND PREDICTION

![Alt text](download.jpg?raw=true)
 
This project aims at giving a snapshot of the emergencies occurring in an area over the period which can help the Emergency Services to make available more resources in the emergency prone area. The distribution of emergencies is shown on the map using Google Maps API. Additionally, the location can be zoomed to provide the emergency category.

![download](https://user-images.githubusercontent.com/20146538/30571719-71db60ce-9c9e-11e7-918b-5d1be0696026.png)
 
The data per week is analysed on an hourly basis to predict the timespan in which the vehicle accidents occurrence is high. This would help the emergency services to make sure that they can deploy more resources at that time of the day.
![download_traffic](https://user-images.githubusercontent.com/20146538/30571819-0264ada8-9c9f-11e7-8476-164d92dfd167.png)

Any emergency type can be compared against another to find the frequency of occurrence. For instance, when there are emergencies of one type occurring more frequently than others, the graph can help the emergency services to allocate the resources accordingly.

Number of fake 911 calls made and the respective cost occured to the police dept is found and the trend is analysed.
Correlation between small business/Home values and Emergency calls is studied and the impact of emergencies is seen data 

##Environment
 - For Windows refer
   - ```http://python.org```
 - For Mac
   - ```pip install virtualenv```
   - To Activate the env
     - ```virtualenv -p /usr/local/bin/python3.6 <project-name>```
     - ### Note ***```if the above step fails make sure python3.6 is installed or check python path using below command```***
     - Run command ```which python```
     - Run command ```source ./<project-name>/bin/activate```
- Now Clone the repo in current directory
  - ```git clone https://github.com/SJSU272LabS17/Project-Team-16.git```
  - ```cd ./Project-Team-16/911emergency/```
- Install the libaries using Pip
  -  ```pip install -r requirements.txt```
- Run the app
  - ```python3.6 app.py```
