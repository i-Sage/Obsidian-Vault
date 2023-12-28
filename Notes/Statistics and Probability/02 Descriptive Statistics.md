24-12-2023 <=> 21:48
=> Type : Note
=> Tags : #statistics 

---
In this chapter, you will study numerical and graphical ways to describe and display your data. This area of statistics is called **"Descriptive Statistics"**. You will learn how to calculate, and even more importantly, how to interpret these measurements and graphs.

A statistical graph is a tool that helps you learn about the shape or distribution of a sample of a population. A graph can be a more effective way of presenting data than a mass of numbers because we can see were data clusters and where there are only a few data values. Statisticians often graph data first to get a picture of the data. Then, more formal tools may be applied.

Some of the types of graphs that are used to summarize and organize data are the dot plot, the bar graph, the histogram, the stem-and-leaf plot, the frequency polygon (a type of broken line graph), the pie chart, and the box plot.

---
#### Stem-and-Leaf Graphs (Stemplots), Line Graphs, and Bar Graphs
- One simple graph, the stem-and-leaf graph or stemplot, comes from the field of exploratory data analysis. It is a good choice when the data are small. To create the plot, divide each observation of data into a stem and leaf. The leaf consists of a final significant digit. for example, 23 has stem two and leaf three. The number 432 has stem 43 and leaf two. Likewise, the number 5,432 has stem 543 and leaf two. Write the stems in a vertical line form smallest to largest. Draw a vertical line to the right of the stems. Then write the leaves in increasing order next to their corresponding stem.

###### Example
For Susan Dean's spring pre-calculus class, scores for the first exam were as follows (smallest to largest):
33; 42; 49; 49; 53; 55; 55; 61; 63; 67; 68; 68; 69; 69; 72; 73; 74; 78; 80; 83; 88; 88; 88; 90; 92; 94; 94; 94; 94;
96; 100

| Stem | Leaf          |
| ---- | ------------- |
| 3    | 3             |
| 4    | 2 9 9         |
| 5    | 3 5 5         |
| 6    | 1 3 7 8 8 9 9 |
| 7    | 2 3 4 8       |
| 8    | 3 8 8 8       |
| 9    | 0 2 4 4 4 4 6 |
| 10   | 0              |
The stemplot shows that most scores fell in the 60s, 70s, and 90s.

>[!note]
>The stemplot is a quick  way to graph data and gives an exact picture of the data. You want to look for an overall pattern and any outliers. An *outlier* is an observation of data that does not fit the rest of the data. It is sometimes called an *extreme value*. When you graph an outlier, it will appear not to fit the pattern of the graph. Some outliers are due to mistakes (for example, writing down 50 instead of 500) while others may indicate that something unusual is happening. It takes some background information to explain outliers



- Another type of graph that is useful for specific data values is a *line graph*.

###### Example
In a survey, 40 mothers were asked how many times per week a teenager must be reminded to do his or her chores. The result are shown in the table below:

| Number of times teenager is reminded | Frequency |
| ------------------------------------ | --------- |
| 0                                    | 2         |
| 1                                    | 5         |
| 2                                    | 8         |
| 3                                    | 14        |
| 4                                    | 7         |
| 5                                    | 4          |

![[Pasted image 20231224221604.png]]

- Bar graphs consists of bars that are separated form each other. The bars can be rectangles or they can be rectangular boxes (used in three-dimensional plots) and they can be vertical or horizontal.

###### Example
By the end of 2011, Facebook had over 146 million users in the United States. The Table below shows three age groups, the number of users in each age group, and the proportion (%) of users in each age group. Construct a bar graph using this data.

| Age groups | Number of Facebook users | Proportion (%) of Face |
| ---------- | ------------------------ | ---------------------- |
| 13-25      | 65,082,280               | 45%                    |
| 26-44      | 53,300,200               | 36%                    |
| 45-64      | 27,885,100               | 19%                    |

![[Pasted image 20231224222010.png]]

---
### Histograms, Frequency Polygons, and Time Series Graphs
For most of the work you do, you will use histograms to display the data. One advantage of a histogram is that it can readily display large data sets. A rule of thumb is to use a histogram when the data set consists of 100 values or more

A *histogram* consists of contiguous (adjoining) boxes. It has both a horizontal axis and a vertical axis. The horizontal axis is labeled with what the data represents (for instance, distance from your home to school). The vertical axis is labeled either *frequency* or *relative frequency*. The graph will have the same shape with either label. The histogram (like the stemplot) can give you the shape of the data, the center, and the spread of the data.

The relative frequency is equal to the frequency for an observed value of the data divided by the total number of data values in the sample. If:
- $f$ = frequency
- $n$ = total number of data values (or the sum of the individual frequencies), and
- $RF$ = relative frequency, 
then:
$$RF = \frac{f}{n}$$
To construct a histogram, first decide how many bars or intervals, also called classes, represent the data. Many histograms consists of five to 15 bars or classes for clarity. The number of bars needs to be chosen. Choose a starting point for the first interval to the less than the smallest data value. A convenient starting point is a lower value carried out to one more decimal place than the value with the most decimal places. For example, if the value with the most decimal places is 6.1 and this is the smallest value, a convenient starting point is 6.05. We say that 6.05 has more precision.
<p align=center>// --snip-- //</p>

---
### Measures of the Location of the Data
The common measures of location are *quartiles* and *percentiles*

Quartiles are special percentiles. The first quartile, $Q_1$ is the same as the $25^{th}$ percentile, and the third quartile, $Q_3$, is the same as the $75^{th}$ percentile. The median, $M$, is called both the second quartile and the $50^{th}$ percentile.

To calculate quartile and percentiles, the data must be ordered from smallest to largest. Quartiles divide ordered data into quaters. Percentiles divided ordered data into hundredths. To score in the $90^{th}$ percentile of an exam does not mean, necessarily, that you received 90% on a test. It means that 90% of test scores are the same or less than your score and 10% of the test scores are the same or greater than your test scores.

Percentiles are useful for comparing values. For this reason, universities and colleges use percentiles extensively.

The *median* is a number that measures the "center" of the data. You can think of the middle as the "middle value", but it does not actually have to be one of the observed values. It is a number that separates ordered data into halves. Half the values are the same number or smaller than the median, and half the values are the same number or larger. 

Quartiles are numbers that separate the data into quaters. Quartiles may or may not be part of the data. To find the quartiles, first find the median or second quartile. The first quartile, $Q_1$, is the middle value of the lower half of the data, and the third quartile $Q_3$, is the middle value, or median, of the upper half of the data. To get the idea, consider the same data set: 1; 1; 2; 2; 4; 6; 6.8; 7.2; 8; 8.3; 9; 10; 11.5

The median or second quartile is seven. The lower half of the data are 1, 1, 1, 2, 2, 4, 6, 6.8. the middle value of the lower half is two.

The number two, which is part of the data, is the first quartile. One-fourth of the entire sets of values are the same as or less than two and three-fourths of the values are more than two.

The upper half of the data is 7.2, 8, 8.3, 9, 10, 11.5. the middle value of the upper half is nine.

The third quartile, Q3 is nine. Three-fourths (75%) of the ordered data set are less than nine. One-fourth (25%) of the ordered data set are greater than nine. The third quartile is part of the data set in this example.

The *interquartile range* is a number that indicates the spread of the middle half or the middle 50% of the data. It is the difference between the third quartile ($Q_3$) and the first quartile ($Q_1$)
$$IQR = Q_3 - Q_1$$
The IQR can help to determine potential *outliers. A value is suspected to be a potential outlier if it is less than (1.5)(IQR) below the first quartile or more than (1.5)(IQR) above the third quartile*. Potential outliers always require further investigation
###### Example
For the following 13 real estate prices, calculate the IQR and determine if any prices are potential outliers. Prices are in dollars.
389,950; 230,500; 158,000; 479,000; 639,000; 114,950; 5,500,000; 387,000; 659,000; 529,000; 575,000; 488,800; 1,095,000

- Order the data from smallest to largest
114,950; 158,000; 230,500; 387,000; 389,950; 479,000; 488,800; 529,000; 575,000; 639,000; 659,000; 1,095,000; 5,500,000

$M$ = 488,800

$Q_1$ = $\frac{230,500 + 387,000}{2} = 308,750$ 
$Q_2$ = $\frac{639,000 + 659,000}{2} = 649,000$ 
$IQR = 649,00 - 308,750 = 340,250$
$(1.5)(IQR) = (1.5)(340,250) = 510,375$

$Q_1 - (1.5)(IQR) = 308,750 - 510,375 = -201,625$
$Q_3 + (1.5)(IQR) = 649,000 + 510,375 = 1,159,375$

No house price is less than -201,625. However, 5,500,000 is more than 1,159,375. Therefore, 5,500,000 is a potential *outlier*.

#### A Formula for Finding the $K^{th}$ Percentile
$k$ = the $k^{th}$ percentile. It may or may not be part of the data.
$i$ = the index (ranking or position of a data value)
$n$ = the total number of data
- Order the data from smallest to largest
- Calculate $i = \frac{k}{100}(n + 1)$ 
- If $i$ is an integer, then the $k^{th}$ percentile is the data value in the $i^{th}$ position in the ordered set of data.
- If $i$ is not an integer, then round $i$ up and round down to the nearest integers. Average the two data values in these two positions in the ordered data set. 

###### Example
Listed are 29 ages for academy awards winning best actors in order form smallest to largest. 18; 21; 22; 25; 26; 27; 29; 30; 31; 33; 36; 37; 41; 52; 55; 57; 58; 62; 64; 67; 69; 71; 72; 73; 74; 76; 77.
1. Find the $70^{th}$ percentile.
2. Find the $83^{th}$ percentile.

$k = 70$
$i = \text{the index}$
$n = 29$

$i = \frac{k}{100}(n + 1) = \left(\frac{70}{100}\right)(29 + 1) = 21$. 21 is an integer, and the data value in the $21^{st}$ position in the ordered data set is 64. The $70^{th}$ percentile is 64 years.

$k = 83^{rd}\quad percentile$
$i = \text{the index}$
$n = 29$
$i = \frac{k}{100}(n + 1) = \left(\frac{83}{100}\right)(29 + 1) = 24.9$, Which is not an integer. Round it down to 24 and up to 25. The age in the $24^{th}$ position is 71 and the age in the $25^{th}$ position is 72. Average 71 and 72. The $83^{rd}$ percentile is 71.5 years.

#### A Formula for Finding the Percentile of a Value in a data set
- Order the data from smallest to largest
- $x$ = the number of data values counting from the bottom of the data list up to but not including the data value for which you want to find the percentile.
- $y$ = the number of data values equal to the data value for which you want to find the percentile.
- $n$ = the total number of data.
- Calculate $$\frac{x + 0.5y}{n}(100)$$ then round to the nearest integer.
---
#### Box Plots
Box plots (also called box-and-whisker plots or box-whisker plots) give a good graphical image of the concentration of the data. They also show how far the extreme values are from most of the data. A box plot is constructed from five values:
- The minimum value
- The first quartile
- The third quartile
- The maximum value.
We use these values to compare how close other data vales are to them.

To construct a box plot, use a horizontal or vertical line and a rectangular box. The smallest and largest data values label the end points of the axis. The first quartile marks one end of the box and the third quartile marks the other end of the box. Approximately **the middle 50 percent of the data fall inside of the box**. The "whiskers" extends from the ends of the box to the smallest and largest values. The median or second quartile can bet between the first and third quartiles, or it can be one, or the other or both. The box plot gives a good, quick picture of the data.
>[!note]
>You may encounter box-and-whisker plots that have dots marking outlier values. In those cases, the whiskers are not extending the minimum and maximum values.

Consider, again, this dataset
1; 1; 2; 2; 4; 6; 6.8; 7.2; 8; 8.3; 9; 10; 10; 11.5
The first quartile is two, the median is 7, and the third quartile is nine. The smallest value is on, and the largest value is 11.5. The following image shows the constructed box plot.
![[Pasted image 20231225073111.png]]
>[!note] 
>It is important to start a box plot with a *scaled number line.* Otherwise the box plot may not be useful.
>

---
#### Measures of the Center of The Data
The "center" of a data set is also a way of describing location. The two most widely used measures of the "center" of the data are the *mean*(average) and the *median*. To calculate the *mean weight* of 50 people, add the 50 weights together and divide by 50. To find the *median weight* of the 50 people, order the data and find the number that splits the data into two equal parts. The median is generally a better measure of the center when there are extreme values or outliers because it is not affected by the precise numerical values of the outliers. The mean is the most common measure of the center.
>[!note] 
>The words "mean" and "average" are often used interchangeably. The substitution of one word for the other is common practice. The technical term is "arithmetic mean" and "average" is the technically a center location. However, in practice among non-statisticians, "average" is commonly accepted for "arithmetic mean".

When each value in the data set is not unique, the mean can be calculated by multiplying each distinct value by its frequency and then dividing the sum by the total number of data values. The letter used to represent the *sample mean* is an $x$ with a bar over it

The Greek letter $\mu$ represents the *population mean*. One of the requirements for the *sample mean* to be a good estimate of the *population mean* is for the sample taken to be truly random.

To see that both ways of calculating the mean are the same, consider the sample: 1; 1; 1; 2; 2; 3; 4; 4; 4; 4; 4
$$\bar{x} = \frac{1 + 1+1+2+2+3+4+4+4+4+4+4}{11} = 2.7$$
$$\bar{x} = \frac{3(1) + 2(2) + 1(3) + 5(4)}{11} = 2.7$$
In the second calculation, the frequencies are 3, 2, 1, and 5.

You can quickly find the location of the center of the median by using the expression $$\frac{n + 1}{2}$$
The letter $n$ is the total number of data vales in the sample. If $n$ is an odd number, the median is the middle values of the ordered data(ordered smallest to largest). If $n$ is an even number, the median is equal to the two middle values added together and divided by two after the data has been ordered. For example, if the total number of data values is 97, then
$\frac{n+1}{2} = \frac{97 + 1}{2} = 49$. The median is the $49^{th}$ value in the ordered data. if the total number of data values is 100, then:
$\frac{n + 1}{2} = \frac{100 + 1}{2} = 50.5$. The median occurs midway between the $50^{th}$ and $50^{st}$ values. The location of the median and the values of the median are *not* the same. The uppercase $M$ is often used to represent the median.

Another measure of the center is the mode. The mode is the most frequent value. There can be more than one mode in a data set as long as those values have the same frequency and that frequency is the highest. A data set with two modes is called a **bimodal**.

---
#### The Law of Large Numbers and the Mean
The law of large numbers says that if you take samples of larger and larger size from any population, then the mean $\bar{x}$ of the sample is very likely to get closer and closer to $\mu$. 

---
#### Sampling Distributions and Statistics of a Sampling Distribution
You can think of *sampling distributions* as a *relative frequency distribution* which a great many samples. Suppose thirty random selected students were asked the number of movies they watched the previous week. The results are in the *relative frequency table* shown below
![[Pasted image 20231225075706.png]]
*If you let the number of samples get very large (say, 300 million or more), the relative frequency tables becomes a relative frequency distribution*

A *statistic* is a number calculated from a sample. Statistic examples include the mean, the median and the mode as well as others. The sample mean $\bar{x}$ is an example of  a statistic which estimates the population mean $\mu$.

---
#### Calculating the Mean of Grouped Frequency Tables
When only grouped data is available, you do not know the individual data values (we only know intervals and interval frequencies); therefore, you cannot compute an exact mean for the data set. What we must do is estimate the actual mean by calculating the mean of a frequency table. A frequency table is a data representation in which grouped data is displayed by calculating the mean of a frequency table. A frequency table is a data representation in which grouped data is displayed by calculating the mean of the frequency table. To calculate the mean from a grouped frequency table, we can apply the basic definition:$$mean = \frac{\text{data sum}}{\text{number of data values}}$$
We simply need to modify the definition to fit within the restrictions of a frequency table.

Since we do not know the individual values we can instead find the midpoint of each interval. The midpoint is $$\frac{\text{lower boundary + upper boundary}}{2}$$
We can now modify the mean definition to be:
$$\text{Mean of the Frequency Table} = \frac{\Sigma fm}{\Sigma f}    \quad \text{where } f = \text{the frequency of the interval and } m = \text{the midpoint of the interval}$$

###### Example
![[Pasted image 20231225080839.png]]

---
#### Skewness and the Mean, Median, and Mode
Consider the following data set.
4; 5; 6; 6; 6; 7; 7; 7; 7; 7; 7; 8; 8; 8; 9; 10
This data set can be represented by the following histogram. Each interval has width one, and each values is located in the middle of an interval.
![[Pasted image 20231225081011.png]]
The histogram displays a *symmetrical* distribution of data. A distribution is symmetrical if a vertical line can be draw at same point in the histogram such that the shape to the left and the right of the vertical line are mirror images of each other.

The mean, median, and the mode are each seven for these data. 

>[!note]
>In a perfectly symmetrical distribution, the mean and the median are the same.

This example has one mode (unimodal), and the mode is the same as the mean and median. In a symmetrical distribution that has two modes (bimodal), the two modes would be different from the mean and median.


The histogram for the data: 4; 5; 6; 6; 6; 7; 7; 7; 7; 8 is not symmetrical. The right-hand side seems "chopped off" compared to the left side. A distribution of this type is called **skewed to the left** because it is pulled out to the left.
![[Pasted image 20231225081552.png]]
The mean is 6.3, the median and the mode is 7. **Notice that the mean is less than the median, and they are both less than the mode**. The mean and the median both reflect the-skewing, but the mean reflects it more.


The histogram for the data: 6; 7; 7; 7; 7; 8; 8; 8; 9; 10, is also not symmetrical. It is **skewed to the right**
![[Pasted image 20231225081814.png]]
The mean is 7.7, the median is 7.5, and the mode is seven. Of the three statistics, **the mean is the largest, while the mode is the smallest**. Again the mean reflects the skewing the most.

>[!summary]
>To summarize generally if the distribution of data is skewed to the left, the mean is less than the median, which is often less than the mode. If the distribution data is skewed to the right, the mode is often less than the median, which is less than the mean.

Skewness and symmetry become important when we discuss probability distributions.

---
#### Measures of the Spread of the Data
An important characteristic of any data is the variation in the data. In some data sets, the data values are concentrated closely near the mean; in other data sets, the data values are more widely spread out form the mean. The most common measure of variation, or spread is the standard deviation. 

>[!Note]
>The **standard deviation** is a number that measures how far data values are from the mean.

##### The standard deviation
- provides a numerical measure of the overall amount of variation in a dataset, and
- can be used to determine whether a particular data value is close to or far from the mean.

##### The standard deviation provides a measure of the overall variation in the data set.
The standard deviation is always positive or zero. The standard deviation is small when the data are all concentrated close to the mean, exhibiting little variation or spread. The standard deviation is larger when the data values are more spread out from the mean, exhibiting more variation

#### Calculating the Standard Deviation
If $x$ is a number, then the difference $x - mean$ is called its deviation. In a data set, there are as many deviations as there are items in the data set. The deviations are used to calculate the standard deviation. If the numbers belong to a population, in symbols a deviation is $x - \mu$. For sample data, in symbols a deviation is $x - \bar{x}$.

The procedure to calculate the standard deviation depends on whether the numbers are the entire population or are data from a sample. The calculations are similar, but not identical. Therefore the symbol used to represent the standard deviation depends on whether it is calculated from a population or a sample. The lower case $s$ represents the sample standard deviation and the Greek letter $\sigma$ (sigma, lowercase) represents the population standard deviation. If the sample has the same characteristics as the population, then $s$ should be a good estimate of $\sigma$.

To calculate the standard deviation, we need to calculate the variance. The *variance* is the *average of the squares of the deviations*(the $x - \bar{x}$ values for a sample, or the $x - \mu$ values for a population). The symbol $\sigma^2$ represents the population variance; The population standard deviation $\sigma$  is the square root of the population variance. The symbol $s^2$ represents the sample variance; the sample standard deviation $s$ is the square root of the sample variance. You can think of the standard deviation as a special average of the deviations.

If the numbers come from a census of the entire population and not a sample, when we calculate the average of the squared deviations to find the variance, we divide by $N$, the number of items in the population. If the data are from a sample rather than a population, when we calculate the average of the squared deviations, we divide by $n - 1$, one less than the numbers in the sample.

##### Formulas for the sample Standard Deviation
$$s = \sqrt{\frac{\Sigma(x- \bar{x})^2}{n - 1}} \quad or \quad s = \sqrt{\frac{\Sigma f(x - \bar{x})^2}{n - 1}}$$
- For the sample standard deviation, the denominator is $n - 1$, that is the sample size MINUS 1.

##### Formulas for the Population Standard Deviation
$$\sigma = \sqrt{\frac{\Sigma(x - \mu)^2}{N}} \quad or \quad \sigma = \sqrt{\frac{\Sigma f(x - \mu)^2}{N}}$$
- For the population standard deviation, the denominator is $N$, the number of items in the population.

In these formulas $f$ represents the frequency with which a value appears. For example, if a value appears once, $f$ is one. If a values appears three times in the data set or population, $f$ is three.

##### Sampling Variability of a Statistic
The statistic of sampling distributions was discussed in Descriptive Statistics: Measuring the center of the data. How much the statistic varies from one sample to another is known as the **sampling variability of a statistic**. You typically measure the sampling variability of a statistic by its standard error. The **standard error of the mean** is an example of a standard error. It is a special deviation and is known as the standard deviation of the sampling distribution of the mean. This will be covered in the [[The Central Limit Theorem]]. The notation for the standard error of the mean is: $$\frac{\sigma}{\sqrt{n}}$$
Where $\sigma$ is the standard deviation of the population and $n$ is the size of the sample.

##### Example
![[Pasted image 20231225090120.png]]

##### Explanation of the Standard deviation calculation shown above
The deviations show how spread out the data are about the mean. the data value 11.5 if farther from the mean than is the data value 11 which is indicated by the deviations 0.97 and 0.47. A positive deviation occurs when the data value is greater than the mean, whereas a negative deviation occurs then the data value is less than the mean. The deviation -1.525 for the data value 9. **If you add the deviations, the sum is always zero**. So you cannot simply add the deviations to get the spread of the data. By squaring the deviations, you make them positive numbers and the sum will be positive. The variance, then, is the average squared deviation.

For the sample variance, we divide by the sample size minus one ($n - 1$). Why not divide by $n$?. The answer has to do with the population variance. The sample variance is an estimate of the population variance. Based on the theoretical mathematics that lies behind these calculation, dividing by ($n - 1$) gives a better estimate of the population variance.

>[!note] 
>Your concentration should be on what the standard deviation tells us about the data. The standard deviation is a number which measures how far the data are spread form the mean. Let a calculator or computer do the arithmetic

##### Standard deviation of Grouped Frequency Tables
Recall that for grouped data we do not know individual data values, so we cannot describe the typical value of the data with precision. In other words, we cannot find the exact mean, median, or mode. We can, however, determine the best estimate of the measures of center by finding the mean of the grouped data with the formula: $$\text{Mean of Frequency Table} = \frac{\Sigma fm}{\Sigma f}$$
where $f$ = interval frequencies and $m$ = interval midpoints.

Just as we could not find the exact mean, neither can we find the exact standard deviation. Remember that standard deviation describes numerically the expected deviation a data value has form the mean. In simple English, the standard deviation allow us to compare how "unusual" individual data is compared to the mean.

##### Comparing Values form Different Data Sets
The standard deviation is useful when comparing data values that come from different data sets. If the data sets have different means and standards deviations, then comparing the data values directly can be misleading.
- For each data value, calculate how many standard deviations away from its mean the value is.
- Use the formula: value = mean + (#ofSTDEVs)(standard deviation); solve for (#ofSTDEVs).
- $\# ofSTDEVs = \frac{value - mean}{standard deviation}$
- Compare the results of this calculation.
---
### References

---