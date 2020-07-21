# ENSF592_Project1_Phase1
This repository stores the files required for running Phase 1 of the ENSF592 Project. Members of this project group are: Jenny (Tong) Xu, Karen (Yunying) Zhang, Patrick (Jung Yu) Kwan.

Attached to this repository are 4 python files:
1. traffic.py : used to upload provided City of Calgary data onto a Mongodb cloud
2. read_db.py : contains all the necessary definitions to read, sort and analyze the City of Calgary Traffic Data stored on Mongodb
3. Map.py : contains all the necessary definitons to produce a map with a marker denoting maximum traffic volume/incidents
4. GUI_main.py : acts as the interface that uses all the definitions in read_db.py and Map.py to show the user plots and maps about Calgary's Traffic data.

# Instructions
1. Run mongod.exe
2. Run monogo.exe
3. Run traffic.py once to add all the traffic data files onto the Mongodb cloud
4. Using the mongo.exe command prompt and type show dbs. This should result in the following output.

CalgaryTrafficAccident2016  0.000GB  
CalgaryTrafficAccident2017  0.001GB  
CalgaryTrafficAccident2018  0.001GB  
CalgaryTrafficVol2016       0.001GB  
CalgaryTrafficVol2017       0.001GB  
CalgaryTrafficVol2018       0.001GB  

5. Run GUI_main.py






