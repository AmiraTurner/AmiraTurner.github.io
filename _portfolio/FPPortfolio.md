---
title : "GES 486 FInal Project Portfolio"
excerpt : "Final project on the study of the effect of socioeconomic factors on education in Baltimore city <br/><img src='/images/portpic.png'>"
collection : portfolio
---

This study focuses on Baltimore City public schools and explores how socioeconomic factors impact educational outcomes. This research builds on my previous work in GES 383, where I analyzed data from the Baltimore Neighborhood Indicators Alliance (BNIA) to understand community dynamics. Previous studies have shown the connection between poverty, race, and educational attainment, which often perpetuate cycles of disadvantage.

The data for this research came from several sources. Information on high-poverty schools was sourced from the Maryland State Department of Education (MSDE) Office of Policy and Fiscal Analysis. Demographic, financial, and educational attainment data were taken from the 2020 American Community Survey (ACS) 5-Year Estimates using R. Community statistical data came from the BNIA website, and Baltimore city school location data were acquired from OpenSource Baltimore.

![image](https://github.com/AmiraTurner/AmiraTurner.github.io/assets/158209865/de1cf25f-2776-4c5b-a3e0-29fde8b532fe)

this map represents the schools that met the critera of a high poverty school in comparison to the rest of them. A new field was created to differentiate between the two catergories and to symbolize them. 

![image](https://github.com/AmiraTurner/AmiraTurner.github.io/assets/158209865/e224b42c-2a8c-430c-81eb-2123b72a3b49)

This map is symbolized by percentage of children living below the poverty line by community statistical area (CSA). The high poverty schools are also shown on the map for location reference.

![image](https://github.com/AmiraTurner/AmiraTurner.github.io/assets/158209865/99e684e3-e4db-433f-b2b0-b5acca6a1134)

This map is symbolized by the percentage of non hispanic african americans per CSA.

![image](https://github.com/AmiraTurner/AmiraTurner.github.io/assets/158209865/edc52029-a580-4fcb-b02b-c49e73c290b0)

This map is symbolized by the percentage of high school dropout and withdrawal rate per CSA. 


You can see that all three maps were darker shaded in similar areas which also encompassed the majority of the high poverty schools. 


Regression Analysis was also performed using variables from the 2020 5 year American Community Survey (ACS). The two variables compared were median household income and estimate of less than high school graduate.

![image](https://github.com/AmiraTurner/AmiraTurner.github.io/assets/158209865/f446e449-3b91-43d8-b2c5-10a79a11e499)

this is a regression significance map that shows strong areas of significance between the two variables. 

![image](https://github.com/AmiraTurner/AmiraTurner.github.io/assets/158209865/36bf9ed0-048b-434a-9974-7198a5142c11)

this is a Moran's I graph showing a negative correlation between median household income and less than graduation education estimates.

![image](https://github.com/AmiraTurner/AmiraTurner.github.io/assets/158209865/b72f9955-ab8e-4d79-a08f-39070b0bbde3)

This is a cluster map showing locations on the map where both variable values are high and low. 



![image](https://github.com/AmiraTurner/AmiraTurner.github.io/assets/158209865/e33af25e-5b4f-4bb0-b723-c1e1b8ef4909)

These are spatial error results from the regression compatison fo the two variables. Based on teh coefficient magnitude and Z-value, it can be stated that median household income has a significant relationship with less than graduation estimates. 


These findings show the relationship between socioeconomic factors and educational outcomes in Baltimore City. High-poverty schools are located in areas with significant financial inequality and higher dropout rates, highlighting the need for targeted interventions. The regression analysis supports the idea that higher income is associated with better educational outcomes, suggesting that economic stability can help students in underprivileged areas. Additionally, the observed racial disparities indicate a need for policies that address both economic and racial inequalities in education.

In conclusion, this research highlights the importance of addressing both economic and racial disparities to improve educational outcomes in urban areas. Census data, community statistical data, and regression map results demonstrate a clear disparity in education and how economic stability ties into it. I wish to do future work looking more into what causes these disparities and what can be done to help it. But overall this was an interesting analysis to do and my findings are interesting although not surprising.














