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

-

![]()

### HAVING

-

![]()

## Conditionals

### CASE WHEN

-

![]()

## Joins

### LEFT/RIGHT

-

![]()

### INNER

-

![]()

### OUTER

-

![]()


## Subqueries

-

![]()
