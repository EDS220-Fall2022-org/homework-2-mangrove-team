Name of the Team
Fishing Team

Description:
For this first stage of the project we will select and interesting dataset, and create some coding lines to visualize and understand the metadata. In this case we are choosing a dataset from Earth Engine to called “GFW (Global Fishing Watch) Daily Fishing Hours”. The values are displayed per band for each finishing activity depending of each gear type. The units are hours. 

We will use this data set to explore the effect of natural global effects like “El Niño 2015” in the finishing industry. We will define a specific location and compare the values of finishing hours from a normal year to a really hot year like the scenario in 2015. 

Here is the link to our data:
(https://developers.google.com/earth-engine/datasets/catalog/GFW_GFF_V1_fishing_hours)

Visuals
Here is an interesting video from the global fishing watch company describing their tool and potential usages. 

https://twitter.com/i/status/1466607715350769665


Installation

For this project we will use our normal python 3 environment, and we have selected the following packages for our project:
ee (Earth Engine)
geemap (Google Earth Engine)
Pandas (Basic python package)
Matplotlib.pyplot (Basic python package)
Numpy (Basic python package)

If you are unsure of how to use Google Earth Engine, or you are having problems initiating the `ee.Authenticate()`, and `ee.Initialize()`, please follow the steps under the webpage of Google Earth Devlopers to help you set the first steps.

https://developers.google.com/earth-engine/guides/getstarted

Metadata Display and Basic Visualization
 
Under the Metadata Display and Basic Visualization seccions we have provided some example commands to take a quick look at what is in your dataset, and how you can access it or index it.
In this case on the GFW data metadata  we are showing what our normal “image”. The function name is `get_image_ids`.
drifting_longlines
fixed_gear
other_fishing
purse_seines
squid_jigger
trawlers
 
For the “Basic Visualization” we are showing in general what the data looks like for specific regions. In this case we are creating a map to show quickly what each layer and pixel values have. 


Roadmap
A potential second stage of the project is to use use all of the vessel track information from the more broad scentario of Vessel Hours and find a “niche” of opportunity in a specific region or MPA you want to study. 


Contributing
The contributions for this repo is open and we would me happy to discuss further steps we can take.

Support

If you have any questions reading this Repo please do not hesitate on sending us an email with your questions. Additionally there is an awesome support area from google earth engine and github that can help you or guide you.
https://github.com/google/earthengine-api
