### 26_GeoJerry
# Topic   : Post Diasater Recovery Assesment and Vulnerability Mapping Using Machine Learning
## Theme   : (5) Diaster Management Application and Land Utilization/Planning  
## Region  : Turkey-Syria

We have choosen two disaster of the region of interest and analysed. 
1)Forest Fire
2)Earthquake

## Forest Fire:
To analyze the land use land cover pattern of the fire affected area Machine Learning techniques are used to classify the region. Just has how the decision trees works random forest also works the same by picking up random pixels and bagging them to each class. Here the four classes are identified and the training samples bags them to each class 
## Post Disaster LULC
![WhatsApp Image 2023-04-29 at 14 35 42](https://user-images.githubusercontent.com/132046555/235304800-adf291fd-e2ea-4b26-93a9-bc6a1f2a4d58.jpg)

### Change Detection Post Disaster
In GEE, the forest fire occurance zone's vegetation index were studied. Google Earth Engine is used to analyze the post disaster effects of Forest Fire on vegetation in Mardin Regions of Turkey. It can be inferred that until the fire occurred a healthy vegetation prevailed in the area of Mardin with an NDVI value of 0.592 which dropped drastically to 0.15 indicating a unhealthy vegetation post the fire occurance.

![WhatsApp Image 2023-04-29 at 14 35 16](https://user-images.githubusercontent.com/132046555/235304044-366f0ec3-98f9-42c7-9d95-dfccd3ee8877.jpg)
![WhatsApp Image 2023-04-29 at 14 35 16](https://user-images.githubusercontent.com/132046555/235304065-ea854dc6-b187-40d1-bcdf-c5ea25c2ef1d.jpg)

## Earthquake:
##### 2023 earthquake data from MAXAR was chosen and using leafmap libary in python, Footprints are visualized

### Footprint :
![image](https://user-images.githubusercontent.com/132046555/235304447-fa1ec2c5-8084-42f1-abc7-94a99233985d.png)
/
### Splitmap :
##### And the pre disaster and post disaster satelitte images were compared and displayed as splitmap.
![image](https://user-images.githubusercontent.com/132046555/235304541-1591b827-a451-4a5b-bca4-a08256264786.png)

This splitmap visualize a clear cut differences by which great insights can be derived about the disaster.
Also, a machine learning model to predict earthquake is moedlled in which it learns from the training set (prior events) and predicts. For machine learning model the kaggle dataset was used as it covered a large span.
(1910-2017)
## Data:
MAXAR 2023 Earthquake : https://raw.githubusercontent.com/giswqs/maxar-open-data/master/datasets/Kahramanmaras-turkey-earthquake-23.geojson
Kaagle (1910 -2017) Earthquake :https://www.kaggle.com/datasets/caganseval/earthquake?resource=download
