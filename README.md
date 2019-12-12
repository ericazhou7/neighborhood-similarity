# neighborhood-similarity
People commonly make comparisons between different cities or even neighborhoods within cities, but how much of these comparisons is grounded in fact versus just a subjective ``feel'' of an area, and can we capture this neighborhood ``essence'' quantitatively? This project aims to build a dataset of important distinguishing features of a neighborhood and cluster similar ones in different cities by developing standardized metrics from various datasets. Using data from many sources such as retail, housing/Airbnb, and more traditional demographics, we create interesting, innovative metrics and eventually categorize different types of neighborhoods.

## Data Processing
Each of the folders NYC and Chicago contain the scripts necessary to clean all the data as well as the original data sets. The full cleaned datasets are located in the cleaned_data folders for each city. They are complete and ready to use, but to replicate the work, one can run the numbered jupyter notebooks in order to create and save the necessary files.

## Interactive Maps
The Map folder contains files for interactive maps that are generated using the Python library Folium. To view the maps, open the deisred html files in a browser. The maps are currently loaded with a sample of ten variables from the dataset. To add or remove features on the map, run the mapgeneration jupyter notebook to regenerate maps with desired feautures. Variables can be added using the function add_layer() and a column label in the dataset.

