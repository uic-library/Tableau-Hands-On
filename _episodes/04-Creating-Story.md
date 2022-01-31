---
title: "Creating Story"
time: 0

objectives:
- "ADD objectives for this page"

keypoints:
- "ADD summary keypoints for this page"
---

- A story in tableau is a sequence of visualizations (either worksheets or dashboards) that help convey information. 
Before we start creating a story, lets create some more visualizations and dashboard. 
- In the earlier section, we focused mostly on sales. In this section, we will create visualizations focused on profits.

Regional Sales and Profits Chart – To visualize the sales and profits of all the sub-categories across the regionswe create a horizontal bar chart.

- First, we add Region from the dimensions list to the columns shelf and then sub-category to rows shelf. 
To observe the sales, we add sales from the measures list to column shelf.
- The visualization created gives us the sales of all the sub-categories of product across all the regions in the US. 
Sort the bar chart in descending order for a better view.Now to observe profits of all the sub-categories across all the regions, 
we make use of colors mark card. When we add profits from measures list to colors mark card, it depicts the profits.
There is a default color palette(orange to blue diverging). To change the color palette, click on the colors mark card and select ‘edit color’.
From the drop down select the color palette which is the most appropriate for the chart.
- For this chart, we select ‘Red-Green Diverging’ color palette. The reason for selecting this palette is that culturally we associate green color to prosperity or progress and red to danger.

<img width="755" alt="Screen Shot 2022-01-24 at 3 10 29 PM" src="https://user-images.githubusercontent.com/47697537/150865440-fce84294-6ac5-4178-8608-8b2db5ea1b2f.png">

Not all viewers have the same visual acuity.Some of them might suffer from colorblindness.
So, selecting such color palette which is colorblind-friendly is important.Blue-Orange is a common colorblind-friendly palette.

- Profit and Sales–To create this graph, we first need to drag the sub-category field from dimensions and drop it in the columns shelf. 
- Next drag the sales from measures and drop it in the rows shelf. This chart shows the sales across sub-category. 
- To add profits, you drag the profits from measures and drop it on the color marks card.

<img width="753" alt="Screen Shot 2022-01-24 at 3 12 42 PM" src="https://user-images.githubusercontent.com/47697537/150865676-e4cbec93-b916-431b-ab8d-3d69741ae7e7.png">

- Profit Trends–To visualize profit trends, add order datemonthto columns shelfand profit to rows shelf.We will then add profits to colors mark card.
- We also changed the month from discrete to continuousand add trend line by right clicking on the white space in the chart and selecting trend line option.

<img width="753" alt="Screen Shot 2022-01-24 at 3 13 42 PM" src="https://user-images.githubusercontent.com/47697537/150865838-ab971d89-f023-4588-83fb-6ba6e33a21a2.png">

- Profit in Dollars–To visualize profits in value we duplicate the sheet and make necessary changes in them.
  - Right click on the sheet name andselect duplicate from the options to duplicate a sheet. Next, select bar chart from the drop down in from the mark cards on the left.

<img width="736" alt="Screen Shot 2022-01-24 at 3 14 42 PM" src="https://user-images.githubusercontent.com/47697537/150865944-d9e62f1c-dd18-4f99-9fba-6e12dcde6e49.png">

- State-wise Profits–Similar to sales by state (Page 6).We change the color palette to red-green diverging

<img width="742" alt="Screen Shot 2022-01-24 at 3 15 22 PM" src="https://user-images.githubusercontent.com/47697537/150866035-937ee57f-b5df-452f-8c5f-e63e7e000ed6.png">

- City-wise Profits–Similar to city by sales (Page 7). We change the color palette to red-green diverging.

- Profits and Discounts–To visualize profits and discounts drag and drop discounts to column shelf and profits to row shelf. 
- Add profits to color marks card and change the palette to red-green diverging.Right click on the chart and add trend line by clicking on ‘show trend line’.

<img width="750" alt="Screen Shot 2022-01-24 at 3 16 35 PM" src="https://user-images.githubusercontent.com/47697537/150866191-977c8e99-9f7f-44f4-ad65-3a4e357c64ad.png">


- Dashboard 1 –Profits Overview–Open a dashboard. Adjust the size option on the left to Automatic. 
- Drag and drop sheets –Profit and sales, Profit trends, Profit in dollars.Arrange the charts in the following way –

<img width="741" alt="Screen Shot 2022-01-24 at 3 17 18 PM" src="https://user-images.githubusercontent.com/47697537/150866289-b2c8f38a-df45-4ca6-bfe6-4d8d5be72398.png">


- From the graph we can see that tables sub-category is the one with high sales and high loss. 
- Let us add a filter to the first graph. By adding filter, we can filter out profit trends and profit in dollars for tables. Click on the filter on the first chart and click on tables.The dashboard will be show profits related to tables.

<img width="734" alt="Screen Shot 2022-01-24 at 3 18 06 PM" src="https://user-images.githubusercontent.com/47697537/150866409-b8ef8a5a-2d87-4c7b-950c-ca3056557aef.png">

- Dashboard 2 –Profit across country–To create this dashboard, drag and drop profit and sales chart, state-wise profitand city-wise profits. 
- Add filter to the profit and sales chart (just like we did in the previous dashboard).

<img width="743" alt="Screen Shot 2022-01-24 at 3 18 50 PM" src="https://user-images.githubusercontent.com/47697537/150866506-2b1d1cc4-63f7-4b78-98ed-a103d831d603.png">


- Dashboard 3 –Profit and Discount–Add profit and sales chart and profit and discount chart. Add filter as added in the previous steps.

<img width="744" alt="Screen Shot 2022-01-24 at 3 19 23 PM" src="https://user-images.githubusercontent.com/47697537/150866588-d8a0795b-b9fd-40d9-b0c1-f700a21c6683.png">


- Creating a story–
- Arranging the charts /dashboards and adding meaningful captions is creating story. Start with a high-level approach of the problem. 
- In our case, the issue is that tables are high in sales but provide the most loss in terms of profit. We then observe the sales trend for the same. 
- We take a look at the geographical distribution and observe that state of Washington and Virginia are doing good. We come to a conclusion by looking at the discounts and profits chart that discounting is not a good option for tables.

<img width="730" alt="Screen Shot 2022-01-24 at 3 20 34 PM" src="https://user-images.githubusercontent.com/47697537/150866802-1f96fbf7-a6a7-4ea5-b5cf-42979ddfc151.png">


<img width="732" alt="Screen Shot 2022-01-24 at 3 20 53 PM" src="https://user-images.githubusercontent.com/47697537/150866851-cabb0787-a08a-46e2-bd2a-551f19d5d8b0.png">


<img width="704" alt="Screen Shot 2022-01-24 at 3 21 10 PM" src="https://user-images.githubusercontent.com/47697537/150866900-8d64104b-1a25-49b6-8f65-d4612a640052.png">


<img width="714" alt="Screen Shot 2022-01-24 at 3 21 32 PM" src="https://user-images.githubusercontent.com/47697537/150866961-ffda2b00-6049-4465-b0cb-6f41f3218e43.png">


<img width="718" alt="Screen Shot 2022-01-24 at 3 21 56 PM" src="https://user-images.githubusercontent.com/47697537/150867015-834d2f33-a081-4ee9-9b08-27f8de0f8f27.png">









