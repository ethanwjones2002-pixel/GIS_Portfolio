# Hi there!
Hello, and welcome to my GIS GitHub portfolio! Below you can find some of the GIS related projects that I've undertaken within the past 4 years of schooling at The University of Montana. 
<br />

Feel free to take a look at my [resume](resume/Ethan_Jones_Resume.pdf)!
## About Me...
<img align="left" 
     src="portfolio pictures/Screenshot 2026-03-01 131537.png" 
     style="width:300px;">

At the time of making this portfolio, I am a senior at The University of Montana earning a bachelor's degree in Foresty, a minor in business administration, a minor in fire science and management, and a certificate in GIS. I was first introduced to the power of GIS through an introductory class my sophmore year, and since then I have delved even deeper into the realm of GIS. 
<br />

My most recent work involves mostly python analysis, which can be viewed below at my [projects](#projects) section. Besides an emphasis on Python use, I have also leveraged the use of GIS applications like ArcGIS Pro and QGIS to conduct various types of geospatial investigations. In some of my other recent projects, a team and I used ESRI's various platforms to explore change relating to wildfires and even create least cost paths to the top of Mt. Everest. You may also view these projects below at my [projects](#projects) section.
<br />

In my future endevors, I hope to continue to use GIS skills to explore and analyze problems relating to the forestry world. Following graduation, I plan on working for Weyerhaeuser at their St. Helens tree farm in Washington as an Intern.

<br />

## Projects
- [Old Growth Identification Within Missoula County (Current)](#old-growth-identification-and-validation-within-missoula-county)
  
- [Python Exploration of Douglas-fir Beetle's Relation to Tree Density using Spatial Autocorrelation](#python-exploration-of-douglas-fir-beetles-relation-to-tree-density-using-spatial-autocorrelation)
  
- [Visualizing Change: the Lolo Peak Wildfire](#visualizing-change-the-lolo-peak-wildfire)

- [An Exploration of Mt. Everest and Least Cost Path Creation](#an-exploration-of-mt-everest-and-least-cost-path-creation)
  
<br />

## Old Growth Identification and Model Validation Within Missoula County

<div>
  <img src="portfolio pictures/Screenshot 2026-03-01 at 2.39.18 PM.png"
       width="500"
       style="float:left; margin-right:20px; margin-bottom:10px;">
       
  <p>
    In my most recent project, I was tasked with analyzing and validating a model that SilvX Labs 
    (a forestry consulting company located within Missoula) created to identify old-growth forests 
    within Missoula County. As an intern, I created a script that identified clusters of prediction 
    values, based on basal area per acre, that fell within the old-growth and intermediate-growth ranges. 
    Then, I created plot locations on these clusters to validate SilvX's predictions.
  </p>

  <p>
    Following the creation of plots, I conducted variable radius forest inventory on 29 plots across 
    Missoula County. At each plot, I collected a latitude and longitude point using a GNSS receiver, 
    along with tree species, DBH, and live/dead status.
  </p>

  <div style="clear: both;"></div>
</div>

### Model Validation Results
<div align="center">
  <img src="portfolio pictures/BAacre Actual vs Predicted.png" width="220">
  <img src="portfolio pictures/TPA Actual vs Predicted.png" width="220">
  <img src="portfolio pictures/TPA Live Actual vs Predicted.png" width="220">
  <img src="portfolio pictures/TPA Dead Actual vs Predicted.png" width="220">
</div>

<br>
<p>
  At the conclusion of my inventory, I compiled all plot-level data into a master dataset to compare 
  my collected measurements with SilvX's predictions. I am currently completing final validation steps, 
  including calculating R² and Root Mean Squared Error (RMSE) to quantify model performance.
</p>

<p>
  You can view the progress of the project 
  <a href="projects/SilvX_Labs_Internship_Data.ipynb">here</a>.
</p>

## Python Exploration of Douglas-fir Beetle's Relation to Tree Density using Spatial Autocorrelation
In this project, my goal was to utilize USDA datasets involving insects and diseases to determine if tree density was a factor in damage to forests. This project was somewhat lengthy and involved two iterations: one with zonal stats, and the other with spatial autocorrelation.
<br />
To view these projects and their data sources download the HTMLs for [interation 1 here](projects/Project_3_Focal_Stats_Iteration1.html) and [interation 2 here](projects/Project_3_Moran'sI_Iteration2.html).
<br />
One key skill that this project demonstrates is the versitle use of python to explore possible hypotheses.

## Visualizing Change: the Lolo Peak Wildfire
<br />

## An Exploration of Mt. Everest and Least Cost Path Creation
<br />
