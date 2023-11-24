# water-and-forest-visualization
Analyse the city to find whether the region is suitable for **Urban Planning** or **Conservation Effort**.

**REQUIRED**

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

You can use **jupyter notebook** or **Google colab** as your desired coding platform.
Google colab --> https://colab.research.google.com

**OVERVIEW**

1. **Geographical map** represent the city - Madikeri, Karnataka
       Download dataset from Overpass Turbo and upload it to colab or any other relavant workspace.
       type map_water_nature to display the geographical map

2. **Heat map** representing both water bodies and nature of that region.
       Paste path of required dataset.Create heat map for water and nature features.
       Type map_water_nature_heatmap to display your heat map.

3. Another way is to represent through the **Choropleth map**.
       Type the code which creates the choropleth map as per your desire.

4. Combination of both waterways and forest area graph.
5. **Bar chart** represent the area distribution of different waterbodies spread across the region.
6. Another **Bar chart** represent the area distribution of forest region.
7. Finally the conclusion/findings about your data visualization.

   Hope this readme file helps you..!
       
