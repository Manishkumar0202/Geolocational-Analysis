# Geolocational-Analysis
This is a project on exploratory analysis on geolocational data. We created this project for the persons who have recently shifted to kolkata and is trying to get a desired place according to their choice and preferences and thus is beneficial for both the restuarants and the person

Firstly, we collect a student dataset where the preferences,income,habits etc. of a student are stored and we take three variables for k-means clustering. Namely, income,exercise, cook. Based on these three criterion we decide the perfect place for the student to reside.

During,the exploratory data analysis of the above data I have used data analysis techniques of machine Learning which helped me to get a clear idea of the dataset and thus heled me in cleaning the data from various nuisances which would be a milestone for a perfect result.
![image](https://user-images.githubusercontent.com/70132091/193410490-4139bf54-e356-434f-8207-9a4ab49a8577.png)

Then, by calling rest API I got the data of various restuarants situated in Kolkata. The data received was in json format where I used some normalization techniques to convert it into a dataframe. Furthurmore, I have used K means algorithm to get the best places. And lastly used folium maker to get the visualisation of te map whose pic is being shown below with the place located in it.

![image](https://user-images.githubusercontent.com/70132091/193410506-a0bf4851-5230-4910-99dd-009c4dbc2f0a.png)

