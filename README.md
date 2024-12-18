# Videogame-Sales

## Data Preprocesing 

1. First, we extract the information of *Ventas+Videojuegos.xlsx*
2. Delete the column *Ventas Global* because is the sum of the region sales and we don't want duplicated information in our dashboard.
3. Convert the columns *Ventas NA*, *Ventas EU* and *Ventas JP* into two columns: **Región:** Name of the region and **Ventas:** Number of copies sold
4. Change the names of *Ventas NA*, *Ventas EU* and *Ventas JP* in *Norteamérica*, *Europa* and *Japón* to represent the region.

## Dashboard Creation 

Once we already have clean data, we proced to create a dashboard for data visualization. 

In the top of the dashboard we have the title and filters for Year, Region, Platform, Genre and Editor. And a restart boton to restart all the filters to the original state (No filters). 

We can apply the filters mention above to obtain relevant information: 
* Sold Copies (Top left number)
* Sales per region (Pie chart)
* Sales by year per region (Bar chart)
* Sales by platform and region (Top left horizontal bar chart)
* Sales by genre and region (Center horizontal bar chart)
* Name of the games, Year, Platform, Genre and Sold Copies (Top left table) 

We can see the dashborad with that information below: 

<img width="658" alt="Dashboard_Videojuegos" src="https://github.com/user-attachments/assets/3eed40e2-92be-4ccf-90e4-c7a2a80aa86c" />

This dashboard serves as a powerful analytical tool for a video game sales company, enabling them to gain valuable insights into market preferences within their specific region. By examining key factors such as genre, platform, and publisher, the company can effectively tailor its stock inventory to align with consumer demand.
