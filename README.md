# Data Visualization Using Python

## Basic Of Visualization and communication
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data. Additionally, it provides an excellent way for employees or business owners to present data to non-technical audiences without confusion.

### 4 Reasons Use Chart
**Comparison**
1. Bar chart vertical (Compare among categories Few category) : A bar graph, as you might guess, uses bars to convey data. The longer the bar, the greater the value. Say a bar graph shows sales per store for the past quarter.
2. Bar chart horizontal (Has long item label) : A horizontal bar chart is a graph in the form of rectangular bars. It's a data visualization technique. The length of these bars is proportional to the values they represent. The bar chart title indicates which data is represented.
3. Line Chart (Compare over time) : Line graphs typically are used to show changes or trends in continuous data over a period of time, with a line connecting the dots that represent the different values. For instance, in a line chart showing a company's stock price over the past week, a line would connect the dots that visualize the change in price each day.
4. Multiple Line Chart (Two or more categories) : A multi-line chart is a basic line chart with one or more additional lines that represent comparison trends.

**Composition & Comparison**
1. Stacked bar chart (show components in an category) : The stacked bar chart (aka stacked bar graph) extends the standard bar chart from looking at numeric values across one categorical variable to two. Each bar in a standard bar chart is divided into a number of sub-bars stacked end to end, each one corresponding to a level of the second categorical variable.
2. Stacked 100% bar chart (focus on contribution on each components) : A 100% stacked bar chart is an chart type designed to show the relative percentage of multiplei data seres in stacked bars, where the total (cumulative) of each stacked bar always equals 100%.

**Composition**
1. Pie Chart (Simple share of total) : A pie chart is one way to display how various parts make up a whole or 100 percent. Each data point is represented by a "slice" of the pie; the slice's size correlates to the percentage of the whole it comprises.
2. Tree Map Chart (Absolute difference matters) : A treemap chart provides a hierarchical view of your data and makes it easy to spot patterns, such as which items are a store's best sellers. The tree branches are represented by rectangles and each sub-branch is shown as a smaller rectangle.

**Relationship**
1. Scatter Plot : A scatter plot identifies a possible relationship between changes observed in two different sets of variables. It provides a visual and statistical means to test the strength of a relationship between two variables.
2. Spatial Map : Spatial mapping makes it possible to place objects on real surfaces. This helps anchor objects in the user's world and takes advantage of real world depth cues. 


## Data Visualization using Python
**Matplotlib**
- Matplotlib is a comprehensive Python library used for both static and interactive data visualization. Visualizations produced by Matplotlib Python can be presented in either 2D or 3D.

**Seaborn**
- Seaborn is a library for creating graphs and statistics using Python. This library is built based on the existing Matplotlib library. Then integrated with the data structure in Pandas.
 
## CRISP-DM
CRISP-DM stands for **Cross-Industry Standard Process for Data Mining**. It is a cyclical process that provides a structured approach to planning, organizing, and implementing a data mining project. The process consists of six major phases:
1. Business Understanding
It has a quite vital part. Business understanding requires knowledge of the business objects, how to build or obtain data, and how to match modeling goals to business goals; so that the best model can be built. Activities carried out include: define business objectives, assessing the current scenario, setting data mining targets, and creating a project plan. 

2. Data Understanding
Data understanding provides the analytical foundation for a study by creating a summary and identifying potential problems in the data. It must also be carried out carefully and not in a rush, such as in data visualization, where sometimes the insight is very difficult to obtain when connected to the summary data. If there are problems at this step that have not been answered, it will interfere with the modeling step.

3. Data Preparation
The data is rarely clean. Data preparation focuses on cleaning and translating raw data into a modelable format. It includes: selecting data, cleaning data, constructing data (feature engineering), integrating data, and formatting data.

4. Modeling
With clean data at hand, numerous modeling strategies are used. Each approach may require specialized data formats, so it is not uncommon to return to the data preparation phase. Key activities include: selecting modeling techniques, designing tests, building the model, and evaluating the model.

5. Evaluation
Evaluation is used to analyze the outcomes of data mining generated during the preceding stage of the modeling process. This is done on the model used in the previous step, with the goal of ensuring that the model determined is consistent with the objectives set in the first step.

6. Deployment
The model is finally deployed in a real-world situation. This might be as easy as creating a report or as complicated as establishing a repeatable data mining process. The key activities include planning deployment, monitoring and maintenance, reviewing the project, and completing the project.


