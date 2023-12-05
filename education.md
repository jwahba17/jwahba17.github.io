# **The state of K-12 schools in Massachusetts – how well are they doing?**

<img src="images/boston-high-school.jpg?raw=true">

Massachusetts is well known throughout the United States as a premier hub for higher education, especially in cities such as Boston. They are also well known for their K-12 school systems: US News and World Report ranked Massachusetts as their number one performing state in the country ([source](https://www.usnews.com/education/best-high-schools/articles/how-states-compare)).

However, it is impossible for every single school to be exceptional. That is a big reason why I wanted to look at how the K-12 schools in the state are doing. It would be awesome to see the variance of how schools of different sizes and types are performing, and to see if there are any trends or patterns we can take away from the data.

I performed this analysis using a dataset from Kaggle which can be found [here](https://www.kaggle.com/datasets/ndalziel/massachusetts-public-schools-data). I strive to answer the following questions:

- Which secondary schools are struggling the most?
- How does class size affect college admission?
- What are the top math primary schools in the state based on 4th grade math standardized exam scores?

I started by importing the dataset into Tableau. There are 1,861 schools in the dataset, with 130 rows of data for each school encompassing everything from school location and enrollment demographics to standardized test scores.

To answer the first question, I create a horizontal bar chart of secondary schools by graduation rate. Some schools with the lowest graduation rates are shown below:

<img src="images/MassSchoolPicture1.png?raw=true">

When creating this bar chart in Tableau, I used diverging colors to signify the graduation rates. The lower the rate, the darker red the bar is. It's clear that the above schools are struggling the most. They may have students from more disadvantaged backgrounds, and these schools should be provided with additional resources to help their students succeed.

Going by the total count of schools, the overall picture appeared to be better. Re-examining the data in Excel, I was able to pull out that out of 374 schools, 216 schools (58%) had graduation rates of 90% and above, while only 158 schools (42%) had a graduation rate of below 90%.

Next, I wanted to examine how class size affects college admissions. To visualize this, I took the average class size in each school and placed it on a scatter plot against the percentage of students who went on to attend college. I also used a third data point – the percentage of economically disadvantaged students. The darker the circle, the higher the percentage.

<img src="images/MassSchoolPicture2.png?raw=true">

The graph shows that there does not appear to be a direct relationship between how large a class size is compared to whether more students attend college. Some of the schools who have the smallest class size and lower percentages of students attending college do appear to be generally more economically disadvantaged.

Now, to look at what the best primary schools for math are in the state. In this scenario, I wanted to pretend that the Massachusetts Secretary of Education believes that 4th grade math is key to the future of students. The state also wants to know which students are above a threshold of 50% of students passing.

Using data based off 4th grade math standardized test scores, I created another horizontal bar chart to visualize what percentage of students received an "Advanced" or "Proficient" score on their exams.

The schools with the highest percentage of students achieving "Advanced" or "Proficient" of 4th grade math exams are shown below.

<img src="images/MassSchoolPicture3.png?raw=true">

Further down on the graph are the schools right above, below, or at the 50% threshold. These schools and those below them will need to put in resources to improve their scores.

<img src="images/MassSchoolPicture1.png?raw=true">

What can we take away from this analysis? Despite having some of the best schools in the country, there is still a wide variance in how schools throughout the state are performing. Some schools who are performing below standards may be able to benefit from drawing resources and ideas from better-performing schools. Since class size does not show a correlation with the percentage of students who attend college, it may not be necessary to make changes there.
