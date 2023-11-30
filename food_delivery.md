**Food Delivery and the Effectiveness of Marketing Campaigns**

!(images/Image1ifood.png){width="5.95in"
height="3.966666666666667in"}

Food delivery has evolved and progressed as consumer technology has
matured. Delivery apps are now cornerstone to many people's everyday
lives, allowing for rapid delivery from restaurants from the tap of a
screen. It has been convenient for me to grab a quick bite to eat when I
don't feel like cooking or leaving the house and has done the same for
many throughout the world.

This project uses a dataset from a Brazilian delivery service called
iFood, where I have analyzed the effectiveness of their marketing
campaigns and drew some very interesting and telling conclusions which
may help guide some critical business decisions. The data set covers a
period of one year.

I answer the following questions in this analysis:

-   What are the most popular months of the year for new sign-ups?

-   How do the age demographics compare of customers who accepted each
    of the marketing campaigns? How successful was one of the campaigns?

-   How does the income level of users compare with the total amount
    spent during the year?

The dataset being used is located
[here](https://github.com/nailson/ifood-data-business-analyst-test/tree/master).
Each row is broken down by customers. Rows with duplicate data were
cleaned up to make the analysis more accurate. A "CustomerID" column was
added to serve as a primary key/identifier for each customer.

The data includes numerous insights into a total of 2,021 customers,
including yearly income, household makeup including kids and teens, age,
visits to the website in the previous month, along with a plethora of
other demographic information. The analysis was all completed in Excel
using several charts and graphs using formulas as well as PivotTables.

To start, I examined the number of sign-ups for each month out of the
sampled data. The data shows that January and March both had the highest
number of sign-ups, with new sign-ups trending downward in the last
three months of the year. A PivotChart was used to produce the below
graph for this trend to be examined:

![A screenshot of a computer Description automatically
generated](./images/image2ifood.png){width="2.2637007874015747in"
height="2.5579013560804897in"}![A graph with green bars Description
automatically generated](images/image3ifood.png){width="5.49315179352581in"
height="3.3in"}

I then compared demographic information on the effectiveness of one of
the marketing campaigns, labeled as "Campaign 6" in the data. Customers
who accepted campaign 6 spent almost double compared to customers who
did not participate (\$564 vs. \$917). This campaign was therefore
successful in getting customers to spend more than they would have on
average.

![A screenshot of a spreadsheet Description automatically
generated](images/image4ifood.png){width="4.695108267716535in"
height="1.7779833770778652in"}

Looking at the average ages of customers, the average age of customers
who accepted each marketing campaign did not vary greatly between each
campaign -- campaign 3 had the lowest average age at around 48, while
those who accepted campaign 4 had the highest average age at around 54.
Most of the campaigns hovered around an average age of 50-51 years old,
with the average age of all customers around 51.

To see if there is a trend associated with the total amount spent for
the year on iFood vs. the customer's income, I created a scatter chart
to better visualize the data, which shows the general trend in relation
to every data point. There is an obvious trend -- generally the higher
the customer's income, the more money they spend on iFood. The data
shows an R-squared value of 0.6711. This means that user income accounts
for 67.11% of the variation in the total amount spent per year. With
good certainty, higher income customers are spending more on iFood's
services.

![A graph showing a number of income Description automatically generated
with medium confidence](images/image5ifood.png){width="6.5in"
height="3.763888888888889in"}

Important conclusions to draw from this analysis:

-   January and March are the most popular months for new sign-ups

-   Each marketing campaign widely attracted the iFood customer base no
    matter the age

-   Campaign 6 was successful in getting the customer base to spend more

-   In general, the higher the income of the customer, the more they
    spend with iFood

Attracting higher income middle-aged customers at the beginning of the
year with a well-planned and executed campaign would be a solid strategy
for iFood's marketing department to focus on to grow their existing
customer base. Or, if iFood wants to focus on an untapped market, they
should attempt to focus more on customers in their 20s and early 30s as
there is a large subset of the population which may not yet be utilizing
their services.
