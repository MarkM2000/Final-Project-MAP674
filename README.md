# Final-Project-MAP674
This is the repository for my final project for MAP674. This project will see me incorporate the features I've learned from the assignments in MAP 674 to try to build a map and analyze it. This shows a step-by-step on how my project will be completed.

## Introduction
This section will introduce the final project. It introduces the topic I plan to use for the project and the initial steps to do the project.
### Topic
### Initial steps
The first thing I will do is create a Jupyter notebook file (`ipynb`), which creates the Python. The file will be named `Final-Project` as a `ipynb` file. I also will install Leafmap on conda, terminal, and on Python as I plan to explore the feature and apply it in the project.

On Python, I will install it by adding `pip install leafmap`. When I import it, I will likely use one of the following on <a href="https://leafmap.org/get-started/">this link</a> or add `import leafmap` into my `ipynb` file. I also created a sample `ipynb` file called `install-leafmap`.

I will create a folder called `assignment`, which is where the `Final-Project` Jupyter Notebook Python file will be located.

## Jupyter File Steps
These are the steps on how I create the Jupyter notebook file.

First, I will import the following Python features into my Jupyter notebook file:

```
%matplotlib inline

import pandas as pd
import geopandas as gpd

import leafmap
```

I will then create several geopandas read files (`gpd.read_file`) consisting of CloudFront files that I plan to use. Stuff I plan to do include clipping points and creating spatial overlays.

## Clipping points
I will be clipping points by using the `gpd.read_file` read files that consist of clipping points.

### Exporting the file
![Exporting](screenshots/Exporting.png)
The `ne_10m_admin_0_countries` file, which was original downloaded from <a href="https://www.naturalearthdata.com/downloads/10m-cultural-vectors/10m-admin-0-countries/">Natural Earth Data</a>. Once downloaded, I will open up the ZIP folder, which is `ne_10m_admin_0_countries.zip` and it will show the files contained in it. The file will be exported as a geojson file, but to do that, I will select `ne_10m_admin_0_countries.shp` from the ZIP folder, and export it as a geojson file. To export the file, right click it select `Save Features As` in the export tab. It looks something like this above, and when finished, select ok.