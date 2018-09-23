# jupyter-real-estate
The project aims to transform the source dataset in order to facilitate the decision of investors regarding the investment option

### The dataset

The dataset assignment_data.csv contains seven fields:
- **id** - unique identification number of the property ad listing
- **title** - title of the property ad listing
- **features** - field with additional characteristics of the property ad listing
- **living_area** - living area of the property in square meters
- **total_area** - total area of the property in square meters
- **plot_area** - plot area of the property in square meters
- **price** - selling price of the property in euros

### The script

The python script organize the dataset to show the group of properties:
- **1.‘apartments’** includes ‘apartment’, ‘penthouse’, ‘duplex’;
- **2.‘houses’** includes ‘house’, ‘villa’, ‘country estate’, ‘moradia', ‘quinta’;
- **3.‘plots’** includes ’plot’, ‘land’.

And their features:
- **Sea view**
- **Garage**
- **Swimming pool**

The final csv file has the following columns: id; location name; type; title; features; pool (0/1); sea view (0/1); garage (0/1), where pool, sea view, garage are binary - 1 if the property is characterised by the feature and 0 if not:
