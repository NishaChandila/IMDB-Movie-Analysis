**# Movies-Analysis**

**In this project, conducted within a Jupyter Notebook using Python, the following steps were undertaken to analyze movies:**

**Step 1:** Importing Python libraries and loading the dataset.

**Step 2:** Dropping irrelevant columns, eliminating null values in genres and director fields, and filling missing values with zeros in production companies.

**Step 3:** Introducing 'profit' at index 3 and 'ROI' (Return on Investment) at index 4.

**Step 4:** Creating a boolean mask to identify NaN values, then utilizing this mask to replace corresponding values with NaN using np.nan.

**Step 5:** Creating df1 and plotting a histogram for the specified data.

**Step 6:** Establishing df2, grouping by release year and ROI, calculating the mean, and plotting a graph.

**Step 7:** Creating df3, grouping by release year and popularity, calculating the sum, and plotting a line graph (showing a rise post-2010).

**Step 8:** Constructing df4, grouping by release year and vote average, calculating the mean, and plotting a line graph.

**Step 9:** Creating df5 and plotting a scatter graph for popularity and vote average.

**Step 10:** Splitting genre values by '|' delimiter and converting them into lists.

**Step 11:** Creating df7, grouping by genre and popularity, summing the values, and plotting a horizontal bar graph (indicating drama, comedy, and action as the top genres).

**Step 12:** Converting release_date into datetime data type and extracting months from it.

**Step 13:** Creating df8, mapping numerical month values, updating them, and plotting a bar graph for popularity against months (highlighting December and June).

**Step 14:** Establishing df9, grouping by month and revenue, mapping numerical month values, updating them, and plotting a bar graph (with peaks observed in June and December).

**Step 15:** Creating df10, grouping by original title and profit, and generating a pie chart depicting the distribution of the top 5 movie profits (Avatar, Star Wars, Jurassic World, The Net, and Titanic).

**Step 16:** Utilizing df11 to generate a pie chart displaying the top 5 production companies (Paramount Pictures, Universal Pictures, Walt Disney Pictures, Warner Bros., and Columbia Pictures).


**Conclusion:**

In conclusion, this movie analysis project, executed within a Jupyter Notebook using Python, delved deep into the dataset to unearth valuable insights. From discerning trends in ROI to unraveling genre preferences and seasonal revenue fluctuations, the analysis provided a comprehensive view of the movie industry landscape. Additionally, identifying top-performing movies and production companies shed light on the key factors driving success in this dynamic domain. Such meticulous analyses not only enhance our understanding of market dynamics but also furnish actionable insights for stakeholders aiming to navigate the ever-evolving entertainment landscape with precision and efficacy.
