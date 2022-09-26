# Tableau-The-three-worst-performing-sub-categories-by-Region

Background: The Sales - Superstore dataset contains detailed information about your company’s sales. Your manager, Sylvia, has decided to cut the three worst-performing sub-categories in their region in terms of Sales.

Objective: To create one data visualization that will identify which three sub-categories are the worst performers by region and show how much worse they perform than other sub-categories. 

Steps to create the visualisation:
1.	Drag ‘Region’ and ‘Sub-Category’ to Rows and AVG(Sales) to Columns and arrange it in descending order.
2.	Show the ‘Region’ filter for selecting one or multiple regions.
3.	Create a calculated field called Rank
RANK(AVG(0-[Sales]))<=3 -Drag this into the color to highlight the bottom 3 sub-categories
Edit Table Calculation for ‘Rank’ and select ‘Specific Dimensions’ ‘Sub-category’.
4.	On the new sheet- Drag ‘Region’ and ‘Sub-Category’ to Rows and SUM(Profit Ratio) to Columns and arrange them in descending order.
5.	Create a calculated field called Rank2
RANK(SUM(0-[Profit Ratio]))<=3
Edit Table Calculation for ‘Rank’ and select ‘Specific Dimensions’ ‘Sub-category’.
6.	Create a dashboard -Drag both sheets on it and edit the filter so that it will be applied to all the related sheets.
7.	Format shading, and font, and give appropriate titles to the dashboard
8.	Now we can view the sub-categories by Average sales and profit ratio by selecting the desired regions.

Link to my dashboard:
https://public.tableau.com/views/Thelowestperforming3subcategoriesbyregion-Superstore/Dashboard1?:language=en-GB&:display_count=n&:origin=viz_share_link
