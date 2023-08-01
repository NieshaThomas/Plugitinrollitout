According to "https://www.visualcapitalist.com/visualizing-all-electric-car-models-available-in-the-us/"

By Omri Wallach. "America’s electric vehicle (EV) market has surged over the last decade, and it’s only expected to grow further." While knowing that americas future is bright we wanted to know how everyday folks were staying in the know and progressing to the future. So with a spend of the globe, I chose to see how the state of Washington was taking this, giant leap for mankind. My data will intel a story of how one American state has shown increase in sales of Electric vehicles. What vehicles are being selected? Weather there meeting the clean alternative requirements? Most importantly, what will be the precentage of increase of sales be by 2024 in the state of Washington.

 As definded, Electric Vehicles have battery instead of a gasoline tank, and as electric motor instead of an internal combustion engine.
Plug-in hybrids electric vehicles are a combination of gasoline and electric vehicles, so they have a battery, and electric motor, a  gasoline tank, and a internal combustion engine. 



    In my search i will pull data from these files to find out features of vehicles. Like requirements, range, make, model, county of purchase by vehicle registration etc. To do this i wil be preforming task on the datasets to request a result of my findings by reading in the data, reviewing the data, requesting information, merge the file, and create a new dataset. After i will include visialization on all desired results. 

    I will start off by importing any needed modules to  call the data into the dataframes. I've chosen to use CSV files for my project. I will be working with a pandas dataframe. my chosen enviroment will be andaconda navigator and jupyter notebook. All files and data will be pushed to github where it will be availbe for your viewing pleasures.


    Tools to be used
Pandas Python 3 VS CODE Anaconda Prompt Anaconda Navigator-Jupyter notebooks

These three datasets shows the battery Electric vehicle(BEVs) and Plug-in Hybrid elecrtric vehicles(PHEVs) that are currently registered, and being sold, through Washington State department of Licensing(DOL).

https://catalog.data.gov/dataset/electric-vehicle-population-data

https://catalog.data.gov/dataset/electric-vehicle-population-size-history-by-county

https://catalog.data.gov/dataset/electric-vehicle-title-and-registration-activity

Varibles used

df = pd.read_csv
df.head()
list(df.columns.values)
df.describe
df.info
df.shape
df.loc
fig
filtered_df
filtered_rate
lables
pattern
projected_sales
sizes
value
x
y
ax
data


In terminal installed pandas - https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html - pip install pandas numpy - https://numpy.org/install/ -pip install numpy metplotlib - https://matplotlib.org/stable/users/installing/index.html - python -m pip install -U pip python -m pip install -U matplotlib seaborn - https://seaborn.pydata.org/installing.html - pip install seaborn In code import pandas - import pandas as pd numpy - import numpy as np metplotlib - import matplotlib.pyplot as plt seaborn - import seaborn as sns Mark downs Sections to explain my code# Plugitinrollitout
After, careful review of this dataset we found that the population of electric vehicles in washington was 135,038
According to the data presented, The state of Washington had registered 1,274 Battary Opeerated Vehicles and 661 Plug-in Hybrid Electric Vehicles. With Battery operated vehicle being the peoples choice.
The sale of electric vehicles had an scenificant increase in the past few years. Sales soared from 1.05 % to 5.40 %. proving this State enthusiam in saving energy for the enviorment.
With sales showing that electric vehicle purcashes were rapid and on the incline and Washington was at top of the market during 2020 and 2022.
