<h1>Performance Report</h1>

<h2>Description</h2>
This project is a comprehensive performance dashboard created using Power BI, designed to analyze the operational data of a plant company. The dashboard provides insights into key business metrics, including Sales, Gross Profit, and Quantity, allowing users to compare Year-To-Date (YTD) with Previous Year-To-Date (PYTD) values. The dashboard is interactive, offering dynamic visualizations that adapt based on user selections, facilitating in-depth analysis and decision-making.
<br />

<h2> Visualization Used </h2>

- <b>Card</b>  <br/>
Cards are used in dashboards to display single values, making them ideal for showcasing key performance indicators (KPIs) at a glance. In this dashboard, Cards are placed in the top section to display key metrics like YTD, YTD vs PYTD, PYTD, and GP% based on the selected slicer value. These KPIs provide an at-a-glance view of the most critical performance data.
<br/>
<img src="https://i.imgur.com/aYVtAe5.jpeg" height="80%" width="80%" alt="Visualization 1"/>
<br />

- <b>Treemap</b>  <br/>
Treemaps are effective in visualizing hierarchical data, allowing users to compare the size of elements within a specific hierarchy. In this dashboard, the Treemap visualization is used to display the bottom 10 countries based on the YTD vs PYTD values for the selected year. This helps in identifying underperforming regions quickly and effectively.
<br/>
<img src="https://i.imgur.com/f4nDBNc.jpeg" height="30%" width="30%" alt="Visualization 2"/>
<br />

- <b>Waterfall Chart</b>  <br/>
Waterfall charts are used to show the cumulative effect of sequentially introduced positive or negative values, making it easier to visualize how an initial value is influenced by a series of intermediate positive or negative values. The Waterfall Chart in this dashboard illustrates the YTD vs PYTD comparison based on the selected slicer value (Gross Profit, Sales, or Quantity). Users can drill down from the monthly data to see performance by country and further by product type, providing a clear view of how different factors contribute to overall performance.
<br/>
<img src="https://i.imgur.com/Zmhf6Ms.jpeg" height="30%" width="30%" alt="Visualization 3"/>
<br />

- <b>Line and Stacked Column Chart</b>  <br/>
This chart type combines line and column visualizations to compare different data series over the same period, making it ideal for showing trends and comparing multiple metrics. In this dashboard, the Line and Stacked Column Chart is used to compare YTD and PYTD values for the selected metric (Gross Profit, Sales, or Quantity) across each month and product type. This visualization helps users track performance trends and identify patterns over time.
<br/>
<img src="https://i.imgur.com/vedVGdZ.jpeg" height="80%" width="80%" alt="Visualization 4"/>
<br />

- <b>Scatter Chart</b>  <br/>
Scatter charts plot data points on a horizontal and vertical axis to show how much one variable is affected by another, making it suitable for identifying relationships and outliers. The Scatter Chart in this dashboard displays account profitability for the selected year, with data points representing the selected slicer value (Gross Profit, Sales, or Quantity) against GP%. It also features a zoom slider, allowing users to focus on specific ranges of data for more detailed analysis.
<br/>
<img src="https://i.imgur.com/ndXhsoF.jpeg" height="80%" width="80%" alt="Visualization 5"/>
<br />

<h2>Dashboard walk-through:</h2>

The dashboard is designed for user interactivity, allowing users to select the year and the metric (Gross Profit, Sales, or Quantity) they want to analyze from the top right corner. Upon making a selection, the entire dashboard updates to reflect the chosen values, including all visualizations and KPI cards.

- Year Selection: This dropdown allows users to choose the specific year they want to analyze, adjusting all YTD and PYTD calculations accordingly.
Slicer Value Selection: This allows users to switch between analyzing Gross Profit, Sales, or Quantity. Once a selection is made, all the charts and cards update to display data related to the chosen metric.
- Dynamic Interaction: The dashboard’s visualizations and KPIs dynamically adjust based on the selected values, providing a tailored view of the data. For example, selecting "Sales" as the metric will update the Treemap to show the bottom 10 countries in terms of Sales YTD vs PYTD, while the Waterfall Chart will display Sales trends over the selected months.
<br/>
<p align="center">
For Year: 2023 and Gross Profit selected  <br/>
<img src="https://i.imgur.com/doNyPnK.jpeg" height="80%" width="80%" alt="Dashboard 1"/>
<br />
<br />
For Year: 2023 and Quantity selected <br/>
<img src="https://i.imgur.com/AjgeT66.jpeg" height="80%" width="80%" alt="Dashboard 2"/>
<br />
<br />
For Year: 2024 and Sales selected <br/>
<img src="https://i.imgur.com/1VrSpZv.jpeg" height="80%" width="80%" alt="Dashboard 3"/>
<br />
<br />
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
