# EMERGENCY 911 ANALYSIS AND PREDICTION

![Alt text](download.jpg?raw=true)
 
This project aims at giving a snapshot of the emergencies occurring in an area over the period which can help the Emergency Services to make available more resources in the emergency prone area. The distribution of emergencies is shown on the map using Google Maps API. Additionally, the location can be zoomed to provide the emergency category.

![picture1](https://user-images.githubusercontent.com/20146538/30572067-724c5746-9ca0-11e7-9c1d-738fb4a0f35a.png)
 
The data per week is analysed on an hourly basis to predict the timespan in which the vehicle accidents occurrence is high. This would help the emergency services to make sure that they can deploy more resources at that time of the day.

![picture2](https://user-images.githubusercontent.com/20146538/30572077-81562082-9ca0-11e7-8eda-e7da53439493.png)

Any emergency type can be compared against another to find the frequency of occurrence. For instance, when there are emergencies of one type occurring more frequently than others, the graph can help the emergency services to allocate the resources accordingly.

Number of fake 911 calls made and the respective cost occured to the police dept is found and the trend is analysed.
![fake](https://user-images.githubusercontent.com/20146538/30572087-919646d4-9ca0-11e7-8f6f-e24cf5ab73a9.png)

Correlation between small business/Home values and Emergency calls is studied and the impact of emergencies is seen data 

![small](https://user-images.githubusercontent.com/20146538/30572085-908cdc62-9ca0-11e7-9f9a-fa7d3ba4687d.png)

![home](https://user-images.githubusercontent.com/20146538/30572089-9295198e-9ca0-11e7-9946-5b1afd7afc6a.png)

## Environment
 - For Windows refer
   - http://python.org
 - For Mac
   - pip install virtualenv
   - To Activate the env
     - virtualenv -p /usr/local/bin/python3.6 <project-name>
     - ### Note ***if the above step fails make sure python3.6 is installed or check python path using below command***
     - Run command: which python
     - Run command: source ./<project-name>/bin/activate
- Now Clone the repo in current directory
  - git clone https://github.com/SJSU272LabS17/Project-Team-16.git
  - cd ./Project-Team-16/911emergency/
- Install the libaries using Pip
  -  pip install -r requirements.txt
- Run the app
  - python3.6 app.py
