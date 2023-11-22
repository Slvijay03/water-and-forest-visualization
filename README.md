# water-and-forest-visualization
Analyse the city to find whether the region is suitable for **Urban Planning** or **Conservation Effort**

Get required geographic data from OpenstreetMap wiki -->  https://wiki.openstreetmap.org/wiki/Main_Page
> Search the required data Ex: waterways you get many data's like
   - waterway=river
   - waterway=canal
   - waterway=stream
   - waterway=drain
   - and waterway=ditch

Get required dataset from Overpass Turbo --> https://overpass-turbo.eu
> Click wizard type "waterways" = "river" and click **build and run querry** to get waterway dataset
> Again click wizard type "natural" = "wood" and click **build and run querry** to get natural dataset

1. Geographical map represent the city - Madikeri, Karnataka
       Download dataset from Overpass Turbo and upload it to colab or any other relavant workspace.
       type map_water_nature to display the geographical map

2. Heat map representing both water bodies and nature of that region.
       Paste path of required dataset.Create heat map for water and nature features.
       Type map_water_nature_heatmap to display your heat map.

