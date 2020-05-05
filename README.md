# Semester-project
Repository for Top/Intro Scientific Program(16362) project

# _Filtering yield data_

<br/>_*Name:*_ Letícia Santos</br>
<br/>_*Semester:*_ Spring 2020</br>
<br/>_*Project area:*_ Agronomy</br>

---

### Objective
<br/> Build a automated routine script that can identify and remove outliers from a yield dataset, with especific parameters.</br>

### Outcomes
<br/> Produce a .csv file with the georeferencied yield data, filtered according to pre-defined limits.</br>

### Rationale
<br/>Georeferenced yield data are one of the best source of information from the field. The data allows farmers to quantify crop yield at small resolutions compared to the tradition method, which consists in large sections. The method enables identify variabilities trough the field and from year to year. The yield data is the mainly information to connect with other environment attributes and develop management systems for each different identified conditon. </br>  
<br/>However, yields datasets from the harvest machine usually have multiple errors. Like the unknown header, the filling/emptying cabine harvest, maneuver time, positional errors and so on. This errors can have effect in the yield analysis and forecast, moreover when you have collected data yield from several years. Thus, remove outliers and pre-process the data is important to make this prediction more accurate and reliable.
<br/>This field has 10 years of yield dataset and has some specific parameters to be cleaned and make this process faster, lighter and automated.</br>
<br/>As the first step, we came up with a scatter plot of the yield value for each coordinate. After that, an general analysis of the dataset was made, the variables were submitted to a histogram. For each variable were stablished a reasonable lower and higher boundry. At the final output, the filtered dataset were submitted to an interpolation and saved in a .csv file.</br>

### Sketch
![image](sketch.png)
