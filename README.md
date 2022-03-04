# bigquery_introduction

Here I will be documenting the steps taken in learning ***Google BigQuery***.

## Fundamentals

### Creating a Dataset

- I created a new dataset named *db_1* in a project called *testproject*:

![](https://github.com/latiful-hassan/bigquery_introduction/blob/main/bigquery_introduction_screenshots/bigquery_dataset.png)

### CREATE TABLE

![](https://github.com/latiful-hassan/bigquery_introduction/blob/main/bigquery_introduction_screenshots/bigquery_create_table_query.png)

### INSERT

- Below I show examples of inserting data with and without specified column names:

![](https://github.com/latiful-hassan/bigquery_introduction/blob/main/bigquery_introduction_screenshots/bigquery_insert_query.png)
![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/table.png)

### Importing Data from Files

- Here I am uploading a csv file to BigQuery:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/import_from_file.png)
![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/cust_upload.png)

### SELECT

- Running **SELECT** & **SELECT DISTINCT** statement:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/select.png)
![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/select_distinct.png)

### WHERE

- Running **WHERE** statement:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/where.png)

### AND/OR/NOT

- Running logical operator statement:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/and.png)
![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/or.png)
![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/not.png)

### UPDATE

- Running **UPDATE** statement:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/update.png)

### DELETE

- Running **DELETE** statement:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/delete.png)

## Sorting & Ordering

- For the following queries, we will be looking at sales data.

### IN/BETWEEN/LIKE

- Finding customers that: live in Seattle or Chicago; are aged between 20 and 30 and customers with first and surnames with 4 letters:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/in.png)
![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/between.png)
![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/like.png)

### ORDER BY/LIMIT

- Ordering the sales in descending order and limiting the results set by 5 rows:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/order_by.png)
![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/limit.png)

## Aggregate Commands

### COUNT

- Counting the number of products purchases and numbers of orders for a specific customer:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/count.png)

### SUM

- Finding the total profit:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/sum.png)

### AVERAGE

- Finding the average commision per sale:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/average.png)

### MIN/MAX

- Showing what the min/max sales are:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/min_max.png)

## Grouping Commands

### GROUP BY

- Here we are finding the numbers of products and grouping by each category:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/group_by.png)

### HAVING

- **HAVING** clauses adds a contraint to **GROUP BY** clauses:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/having.png)

## Conditionals

### CASE WHEN

- Here we are creating a new column based on the conditional, so that each region has an associated HQ location:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/case.png)

## Joins

- For this section, two new tables were created: *customer_age* which is all customers aged between 20 and 60, *sales_2015* which is compreised of all sales data for the year 2015.

### LEFT/RIGHT

- Results return unmatched data from either the left/right table:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/left_right_join.png)

### INNER

- Results return only matched data:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/inner_join.png)

### FULL

- Results return all data when there is a match in either left or right table:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/full_join.png)


## Subqueries

- Here we are using a **Subquery** in the **LEFT JOIN FROM** clause to find the sum of quantity from the *sales* table and join it to the *products* table:

![](https://github.com/latiful-hassan/bigquery_introduction_inprogress/blob/main/bigquery_introduction_screenshots/subquery.png)
