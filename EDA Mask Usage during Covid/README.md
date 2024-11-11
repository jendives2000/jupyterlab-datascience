![image](https://github.com/user-attachments/assets/b63e85d2-f2ec-4477-b1b0-fa70caf5efa5)


This is a side project that I am doing to practice Pandas 2 and EDA, particularly preprocessing and visualization. 
A substantial part of this work was dedicated to converting Series data types to pyarrow data types.  
This is a best practice that is not so impactful here in this case where the column with the highest number of rows is about 5000 rows.  
Still, it saves some time in computing and memory weight as well. Whenever it was the case I mentioned it in the notebook.

For all details related to the data itself, please refer to the fundamental_analysis.md document. 

After you downloaded the code locally, make sure to:
- change the path of the 2 csv files found in the folder data
- change the path to the 2 shp files found in the folder maps

If you use any of my work, please send me an email at jy.tran@datascience-jy.com along with details about where and why you are using it. Thank you.
Feel free to send a thank you otherwise, connect on LinekdIn and/or X.

## Pandas Modules
- pandas itself of course
- matplotlib
- geopandas (only if you want to visualize the US map)
- shapely.geometry
  --> Point and box (only for the US map too)



---
