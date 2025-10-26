# Choropleth Vaccination Maps

A map engine I created using publicly avaiable health data which covered various vaccination programmes broken down at ICB level. <br>
The engine helped significantly in allowing me to protype and demonstrate various methods of shading along with colour schemes for each. <br> 
Through 3 iterations we landed on some final products that blended NHS colour schemes with the performance scale. <br>

## The components needed to achieve this are: <br>
**csv** - This is report_standards meta_data_2 file, this allows control of the parameters such as colour scheme and text annotations on the cbar <br>
**geopandas and geojson** - not included in this repo but can be found on ONS - for plotting the boundaries <br>
**data**  -  One I manually put  together through various public gov websties for each programmes. The ICB code needed for the join to geojson <br>
**python notebook** - a python notebook for applying the transformations and reading in the control csv, data and geojson. <br>



<img width="529" height="353" alt="image" src="https://github.com/user-attachments/assets/bdf19397-bc2f-45a7-ae0f-d41edcbd55c5" />


![flu_65](image.png)

![maternal_pertussis](image-1.png)