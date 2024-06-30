# Saving SuperStore

The superstore is in peril! You have been hired as a consultant to review the superstore’s operations and increase its profitability to avoid bankruptcy.

For each question, you should prepare an individual visualization that justifies your conclusion.

![SuperStore](image_link)

## Part 1: Profits & losses

First, we'll try to identify the important centers of profit and loss for the superstore.

1. Among the pairs of dimensions (e.g., subcategory + region, or shipping mode + product ID) which are the two biggest profit centers and two biggest loss-makers? Justify your conclusion with a visualization.
2. Which products should the superstore stop selling? Justify your conclusion with a visualization.
3. Which product subcategories should the store focus on and which should they stop selling? Choose 3 of each.

## Part 2: Advertising

The superstore wants to know if advertising would be worth it. Advertising works over time and geography, and your average profit per unit sold should be high enough to justify it.

1. Identify the 3 best combinations of states and month of the year to advertise in. Make a visualization of the average profit for each month of the year for those 3 states and argue how much you would be willing to pay in advertising for those states in those months.
2. You should be most willing to pay for advertisements based on the return on ad spend ratio. Let's say you should be willing to spend 1/5 of profits on advertising for this exercise.

## Part 3: Returned items

In the last part, we’ll use the Returns table to see if some products have abnormal rates of being returned to the store.

**HINT:** Make sure the Returns table is LEFT JOIN’ed onto the Orders table. You should see both “Yes” and “null” values in the Returned column.

1. Make the Returned field into a calculated field where the null values are 0 and the Yes values are 1.
2. Use this new field to make a visualization for each of the following questions: 
   1. Which products have the highest return rate? 
   2. Which customers have the highest return rate?
3. In a separate sheet, make a visualization of the average profit against the average return rate on a dimension of your choice (state, shipping mode, product type, etc.). Present a visual argument why the superstore should do away with or keep doing business on the basis of this dimension.

## Part 4: Submitting your project

You need to submit a ZIP archive of your project. It should include:

- `README.md` file with a link to the workbook on Tableau Public's server (publish your dashboard on Tableau Public and insert the link to it into `README.md`).
- All of your files (including additional files as needed — just make sure they are no more than 9 megabytes in total).

You'll receive an archive in return, with the reviewer's comments inside each file.
