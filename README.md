# Data-Visualization-Projects

PROJECT 1 
The group will analyze a dataset using the libraries of python we have seen.
Dataset choice: You can choose the dataset you want. The dataset you use does not need to
be too large. However, it must contain interesting data and some structure. Some links when you
can check for a dataset are the followings: http://www-personal.umich.edu/~mejn/netdata/ and
http://snap.stanford.edu/data/.
Please notify us by email the dataset you chose and wait for our confirmation before
starting the analysis. If you cannot chose a dataset let us know by email and we will assign one to
you.
2 Expected outcome
The project will be valued 14 points and will make for 40% of your final grade. Your team is required
to submit :
(1) A folder containing the code related to the project and a pdf containing the results (figures,
values, etc.) OR a single Jupyter notebook containing both code and results.
(2) A small report of at most 5 pages (figures excluded).
(3) A file pdf/ppt containing the presentation of the results.
We detail now what we expect in each of these points:
(1) The code folder:
You should submit one or more files that allow to reproduce all the results you have claimed. The
dataset should not be included but it has to be available from a link. If you have a doubt whether
to include or not a file just ask us! Your code should allow for the following points:
Plots You should make at least two different types of plots that answer different questions. These
plots should be done using Seaborn and/or Plotly libraries and at least one of them allow for
some animation/interaction as you have seen in class. The plots must enable you to extract
interesting insight from the data. Feel free to use even more complex constructs that were not
covered in the course.
Network analysis You should be able to extract a network from your dataset. Use the networkX package to describe
different structural properties of your network (is it connected? bipartite? scale-free? what is
the diameter? etc). You should compute at least two of different measures among the ones
seen in class, to determine the importance of the nodes. Be prepared to explain your choice and
comment your results.
1
Network Visualisation Use one of the tools seen in class (as for example Gephi) to visualise your network. Experiment
with different layouts for your visualization. Which one do you prefer and why?
(2) The report file:
It should not be more than 5 pages and it should contain: (i) the description of the dataset, its format,
if you have perfomed any cleaning or modifications, (ii) the discussion of the results of your plots and
network analysis and eventually the reasoning behind the choices you made (if any). Here you can
include also all the figures and information that are not explicitly included in the presentation file.
Important: If you prefer you can also decide to include all the comments and the information of
the report into your jupyter notebook. In that case you do not need to include also a report file or
any figures (if they already appear in the notebook).

PROJECT 2 
For this assignment we will use the following dataset available in https://www.kaggle.com/prasert
k/healthy-lifestyle-cities-report-2021 but also in the course website on luiss.learn. The dataset
contains 10 healthy living metrics in top 44 cities measured on 2021.
Each row in the assignment datafile corresponds to a city. The following variables are provided to you:
(1) City Rank, (2) Sunshine hours, (3) Cost of a bottle of water, (4) Obesity levels, (5) Life expectancy (years
per Country), (6) Pollution (Index score), (7) Annual avg. hours worked, (8) Happiness levels (Country) (9)
Outdoor activities (City), (10) Number of take out places(City), (11) Cost of a monthly gym membership
(City).
Familiarize yourself with the dataset, then write a Python code for the following questions:
(a) Check if the dataset has missing values and choose a way to correct them. Motivate your choice. (0.25
points)
(b) Plot a bar chart describing the Happiness levels for each city. The bars should be colored in gray
except for the bars corresponding to Italian cities which should be colored in dark blue. (0.25 points)
(c) Plot the correlation between any two pair of variables as a heatmap with a custom palette. What can
you say about the result? (0.5 points)
(d) Divide the cities into 6 groups based on the first letter of their name (A-D, E-H, I-L, M-P, Q-U, V-Z).
Plot a bar chart for the “Number of take out places” variable with six bins (A-D, E-H, I-L, M-P, Q-U,
V-Z). Each bin contains the sum of the values of “Number of take out places” for the cities that fall
in that bin. (0.75 point)
(e) Plot the graphics as described in Figure 1 (0.75 point).
Make the visual nice and select wisely what kind of palette apply for each figure! Leverage principles
from what we have seen in this course when developing your solution. Consider issues such as legends, labels,
and chart junk. We will also take into account the quality of your code.
Format: You have two possibilities: (1) You submit in a single zip folder: the python code and all files
corresponding to the figures produced (2) You submit a single Jupyter Notebook with your code.
