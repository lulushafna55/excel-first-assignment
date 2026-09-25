# excel-first-assignment
formulas

1) Sum, Count, Average:	
	• What is the total price of all products in the dataset?
=SUM(G2:G35)
	• How many products are there in the dataset?
=COUNT(G2:G35)
	• Calculate the average price of the products.
=AVERAGE(G2:G35)

2) Min and Max:	
	• Determine the minimum price among all products.
=MIN(G2:G35)
	• Find the maximum price among all products.
 =MAX(G2:G35)

3) IF Function:	
	• Using an IF function, create a new column named Price Range to categorize products with a price greater than or equal to $500 as 'High Price' and others as 'Standard Price'.
	=IF(G2>=500,"High price","standared price")

  4) SUMIF and COUNTIF:	
		• Calculate the total price for products in the 'Electronics' category using the SUMIF function.
=SUMIF(J2:J35,"electronics",G2:G35)
		• Determine the count of products with a price less than $100 using the COUNTIF function.
=COUNTIF(G:G,"<100")

			5) Text Formatting - LEFT, RIGHT, MID:	
		• Create a new column named Day with the first 2 characters of each 'Product ID' using the LEFT function.
=LEFT(A2,2)
		• Create a new column named Country Code by extracting the last 2 characters from the 'Product ID' column using the RIGHT function.
=RIGHT(A2,2)
		• Create a new column named Month by extracting 4th to 6th characters from the 'Product ID' column using the MID function.
=MID(A2,4,3)

		





   


