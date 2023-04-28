# Project 8 Personal Data Visualization

# Part 1: Extracting timestamps from your personal data
Import at least one of your personal data files into a Jupyter notebook
Parse the data into a dataframe
Extract just the timestamps into a new dataframe
Export that new dataframe as a .csv file (using to_csv()Links to an external site.).
If you need more guidance, check out the instructions from the in-class activity where we did this in this Jupyter notebook Download this Jupyter notebook.
# Part 2: Analyzing timestamp data for patterns
Import your partner's timestamp data into a Jupyter notebook. Using Python and pandas, complete the following:

Make sure the timestamp is in the datetime format (for example, by using pandas.to_datetime.Links to an external site.
Using pandas.diff()Links to an external site., make a new column that tells you the time since between a timestamp and the previous one (for example, row 2 will have the time between the timestamp in row 2 and row 1). (TIP: Make sure your timestamps are sorted in chronological order before you do this!)
Answer: What is the longest time between timestamps? What is the average time between timestamps?
Answer: What is the day with the most timestamps? How many events (timestamps) were on that day? (TIP: Once you have done .to_datetime, you now have a Timestamp object, which has all kinds of cool properties and methods -- such as returning the day or the month. Find out more hereLinks to an external site.. You might also want to use DatetimeIndexLinks to an external site.. For example, you can create a new column that is the day by doing: df['days'] = pd.DatetimeIndex(df['timestamps']).day )
Answer: What is the month with the most timestamps? How many events (timestamps) were on that month?
Answer: What do you think the source of this data is? Write a few sentences explaining your reasoning. What other data might help you verify if you are correct?
Exchange your analysis with your partner. Read your partner's analysis -- does it seem accurate? Did they guess the correct data source (or type of data source)?
For the days and months that your partner identified as having the most timestamps, try to figure out what was happening on those days. What other data might help you figure this out?

# Part 3: Make a combined visualization
Using both partners' timestamp data, make a visualization that shows the distribution of events over time for both people. For this part, use Python and Jupyter notebook, plus matplotlib/pyplot or Seaborn.

# Part 4: Analyze and visualize an additional element from  your personal data
The analysis includes:
At least two clear questions that you ask and then answer via data analysis
At least one form of data manipulation (calculating new values, doing a groupby, etc.)
At least one visualization (you can use any tool you like: Observable, Seaborn, Flourish, etc.)
For this portion of the project, do not include your code or your raw data -- that is personal and you can keep it private! You just need to include your results (i.e. findings from your analysis) and your visualization.
