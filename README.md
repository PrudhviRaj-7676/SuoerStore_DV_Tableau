Our aim is to 
•	Analyse the profit of respective state and 
•	To find out each city’s contribution in that profit.


Level of details (LOD) in Tableau  : 
Level of Detail (LOD) expressions in Tableau allow you to control the granularity of your data calculations. 

There are three types:

Include LOD Expressions: 
These add specified dimensions to your calculations, allowing for more detailed analysis. 
   For example, { INCLUDE [Customer Name]: AVG([Sales]) } calculates the average sales per customer within a broader view.

Exclude LOD Expressions: 
These remove specified dimensions from your calculations, rolling up the data to a higher level of granularity. 
   For example, { EXCLUDE [Category]: SUM([Sales]) } calculates the total sales per region, ignoring product categories.

Fixed LOD Expressions: 
These set a fixed level of detail for your calculations, independent of the view's dimensions. 
   For example, { FIXED [Customer Name]: SUM([Sales]) } calculates total sales per customer across the entire dataset.

LOD expressions provide flexibility and precision, enabling you to tailor your data analysis to specific needs, ensuring accurate and insightful visualizations.
