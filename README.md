<h1>Data Analysis with Excel</h1>

<h2>Description</h2>
Analysis for Australian Energy firm. Started with 2 csv files. First one - date and informations about holidays and school days, second one with date, weather conditions, energy demand and RRP values.
<br />

<h2>Analysis walk-through:</h2>

<p align="left">
Data after some processing (formatting date column to show day of the week, month, week of the year and year), using VLOOKUP to find school/holidays days, simple calculations (revenue values), conditional formatting (weather bars, color formatting in demand and revenue columns to to show high/low values): <br/>
<br></br>
<img width="1203" alt="Demand" src="https://user-images.githubusercontent.com/129959595/234535200-95cd913f-d8a4-402d-80ea-d6bb1636fe48.png"/>
<br />
<br />
Summary tables with using formulas:  MAX, MIN, MEAN, MATCH , INDEX, MAXIFS, MINIFS to find Min, Max, Mean values & Min/Max Saturday/Sunday values with dates when this occurred: <br/>
<br></br>
<img width="870" alt="Summary tables" src="https://user-images.githubusercontent.com/129959595/234535817-78029f29-67c3-4a15-99ef-a058f4d885e9.png"/>
<br />
<br />
Comparison of 20 top & 20 bottom energy demands values to analyse if there is present any dependency between values :  <br/>
<br></br>
<img width="787" alt="Top Bottom" src="https://user-images.githubusercontent.com/129959595/234537059-d35b47ea-4f4e-417c-8bc5-43a7e6572789.png"/>


<br />
<br />
Chart showing energy demand values over time to find pattern and make some conclusions: <br/>
<br></br>
<img width="1079" alt="Over time" src="https://user-images.githubusercontent.com/129959595/234536029-50bd8f73-d54e-49fd-8154-540902a5a4ab.png"/>

<br />
<br />
Charts showing effect of weathers on energy demand values to analyse if there is present any dependency between weather conditions and energy demand values:  <br/>
<br></br>
<img width="832" alt="Weathers" src="https://user-images.githubusercontent.com/129959595/234536315-4c842c3d-513e-485c-95b7-1d860111b072.png"/>
<img width="794" alt="Weathers2" src="https://user-images.githubusercontent.com/129959595/234536369-0baf035a-fe83-4aae-b8aa-2a1df143e367.png"/>

<br />
<br />
Charts showing effect of max temperatures and holidays days on energy demand values to analyse if there is present any dependency between temperatures & holidays/school days and energy demand values:  <br/>
<br></br>
<img width="943" alt="Temp   Holidays" src="https://user-images.githubusercontent.com/129959595/234537493-a8cacd05-6920-413e-8a97-5697c5f56fbb.png"/>

<br />
<br />
Pivot table with conditional formatting showing energy demand values on days of the week, week of the year and year to show dependency:  <br/>
<br></br>
<img width="1422" alt="Pivot table" src="https://user-images.githubusercontent.com/129959595/234537629-f7a8dfa1-78e4-4f0c-9a3c-15347ac4517f.png"/>

<br />
<br />
Chart showing year on year energy demand values to show patterns trough years:  <br/>
<br></br>
<img width="799" alt="YoYdemand" src="https://user-images.githubusercontent.com/129959595/234537812-144bddda-ee7e-4726-bca3-25cd1c736ece.png"/>

<br />
<br />
<h2>Conclusions: </h2> <br/>
<br> ✔️ Energy demand have some patterns trough each year which are not changing</br>
<br> ✔️ Energy demand slighty going down with each year but not changing much over time</br>
<br> ✔️ Energy demand depends the most on Temperatures & Reinfall values (extreme temperatures and no rain results in highest energy demand values) </br>
<br> ✔️ Holidays days don't change much in energy demand values, they are just slightly lower than school days values</br>
<br> ✔️ Energy demand values are the lowest on Saturdays/Sundays</br>
<br></br>
<h2>Additional knowlege:</h2>
<br>✔️ Data Lifecycle</br>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
