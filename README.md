# TikTok Claim Analysis
<br>![750px-TikTok_logo svg](https://github.com/jmcs50/tiktokclaimanalysis/assets/93098571/5f6d5cc4-d1bb-4e0e-9293-52f66bc7cdb7)
</br>
<br>
## What are the differences between claim videos and opinion videos. 

## 1. Business task
Show data structuring and cleaning, as well as using Exploratory Data Analysis (EDA) and data visualization for matplotlib/seaborn and Tableau to understand how claim videos differ from opinion videos.

● **What is the problem you are trying to solve?** <br/>
What distinguishes claim videos from opinion videos.

● **How can your insights drive business decisions?** <br/>
Insights can provide context into virality of videos that have stronger user engagement in addition to identifying the impact of videos that are associated with an author's ban status and how that correlates as well with user engagement. These can then drive business engagement in how claim videos differ from opinion videos.
<br/>
<br/>

## 2. Description of all data sources used 
The data being used has been made available by Google as a downloadable .csv file.

**● Where is the data located?** <br/>
Data is located on local Desktop that was obtained as .csv zip file originating from <i>Go beyond the numbers translate data into insight</i> course under <i>Module 5: Activity: Create your Course 3 TikTok project</i>.

**● How is the data organized?** <br/>
Data for is organized into 12 columns with 19382 entries and int64, object and float63 data types:<br>
![image](https://github.com/jmcs50/tiktokclaimanalysis/assets/93098571/8b44ed4a-7c18-4802-9aab-3c8d4efe3bd9)


**● Are there issues with bias or credibility in this data?** <br/>
The original data source cannot be confirmed and there are 298 rows that are missing values.<br/>
**Reliability :** There are 298 rows with missing values. This may have an impact on the reliabilty of the data being presented.<br/>
**Originality :** Not able to confirm the originality of the data that has been provided.<br/>
**Comprehensive :** The dataset provided is comprehensive and contains information needed in order to analyze the problem being presented.<br/>
**Current :** No dates have been provided so the date of the dataset provided is unknown.<br/>
**Cited :** Original source is unknown, however Google has provided the dataset.<br/>

**● How are you addressing licensing, privacy, security, and accessibility?** <br/>
No restrictions have been documented limitating the personal or commercial use of the dataset provided. There are no identifiers provided in the dataset that can be used to identify individual users.

**● How did you verify the data's integrity?** <br/>
Using data.info() and data.describe() to determine any anomalies.

**● How does it help you answer your question?** <br/>
The use of data.info() assisted in identifying how many rows were missing values and data.describe() was used to identify any negative numeric values which be abnormal for the dataset being analyzed.

**● Are there any problems with the data?** <br/>
The main issue is the 298 rows that are missing values and the inability to add the missing values needed.
<br/>
<br/>
## 3. Documentation of any cleaning or manipulation of data
**● What tools are you choosing and why?** <br/>
I am using Jupyter Notebook to clean and analyze the data and using both Jupyter Notebook and Tableau to visualize the data. I have used Jupyter Notebook and Tableau to visualize the data as Jupyter Notebook provided me with the opportunity to document the steps I took with cleaning and analyzing data and get an initial insight into the data visualed. I picked Tableau for the final visualation as I was interested in creating a dashboard and story.

**● Have you ensured your data’s integrity?** <br/>
Yes, the decision was made to leave the missing values at it represented only 1.5% of the dataset.

**● What steps have you taken to ensure that your data is clean?** <br/>
The use of data.info() assisted in identifying how many rows were missing values and data.describe() was used to identify any potential negative numeric values.

**● How can you verify that your data is clean and ready to analyze?** <br/>
With the use of data.describe() I was able to identify any potential negative numeric values which in this case there were none.

**● Have you documented your cleaning process so you can review and share those results?** <br/>
The cleaning and analysis process has been documented in Jupyter Notebook.
<br/>
<br/>
## 4. Summary of analysis
A TikTok videos engagement is strongly correlated with its claim status. In the dataset provided the TikTok videos tagged as a Claim and Opinion status were almost equal in count, howver when comparing this information agains the total amount of views received for each status, those that have been tagged with a Claim status there are 501,029 videos watched compared to only 4,956 for Opinion status. This equals to less than 1% for Opinion status videos watched.

When analyzing likes, and views these are all heavily skewed towards 100,000 of less with like counts over this amount more evenly distributed and those for view significantly declining as the count increases. For downloads and comments they are in the lower range with the majority of downloads under 100 and heavily declining above 100. The same can be said for video comments which are also under 100 and progressively decline.

The number of Active authors whose videos have been tagged as Claim or Opinion make up a large portion of the videos. There are also more Active authors whose videos have been tagged as an Opinion. The median number of views for Banned authors are over 400,000 versus the median number of views for Active authors which are under 50,000. This indicates videos going viral and obtaining a large amount of user engagement.

**● How should you organize your data to perform analysis on it?** <br/>
Data was organized to compare counts for different categories against its claim status.

**● Has your data been properly formatted?** <br/>
Data has been properly formatted with column data types corrected to match field values.

**● What surprises did you discover in the data?** <br/>
The data shows how viral videos can heavily impact user engagement on the TikTok platform and that a very large portion of the dataset had lower user engagement.

**● What trends or relationships did you find in the data?** <br/>
A trend found what that a user who was banned had more user engagements than those that were still active.

**● How will these insights help answer your business questions?** 
These insights will assist with the machine learning model that is created to predict whether a video is a claim or opinion.
<br/>
<br/>
## 5. Supporting visualizations and key findings
Supporting visuals were created with Tableau and key findings are notated further down in report.

**● Were you able to answer the question of how do videos tagged as a Claim differ from videos tagged as an Opinion??** <br/>
Yes, differences were identified such as the amount of views a Claim status video receives in comparison to one tagged as an Opinion.

**● What story does your data tell?** <br/>
The story the data tells is that while there were a relatively even amount of TikTok videos tagged as a Claim and Opinon the amount of views received was heavy on for Claim status. Additionally the majority of videos have lower counts of overall user engagement with liking, commenting and downloading.

**● How do your findings relate to your original question?** <br/>
Differences were able to be identified between Claim status and Opinion status TikTok videos.

**● Who is your audience? What is the best way to communicate with them?** <br/>
Data team:<br/>
    Willow Jaffey- Data Science Lead<br/>
    Rosie Mae Bradshaw- Data Science Manager<br/>
    Orion Rainier- Data Scientist<br/>

Cross-functional team:<br/>
    Mary Joanna Rodgers- Project Management Officer<br/>
    Margery Adebowale- Finance Lead, Americas<br/>
    Maika Abadi- Operations Lead<br/>

The best form of communication is through email and a final a powerpoint presentation with findings.

**● Can data visualization help you share your findings?** 
Data Visualizationwas used to visualize view, like, comment and download counts again claim status in addition to visualizing author banned status against claim status.

**● Is your presentation accessible to your audience?** 
Presentation is in a Tableau dashboard and story format.

![Dashboard](https://github.com/jmcs50/tiktokclaimanalysis/assets/93098571/b92c1ac6-b52c-426c-906f-b439df6b5292)
<br/>
<br/>
## 6. Key Takeaways 

1. There are significantly more Active authors with a Claim or Opinon than those Under Review or Banned.
2. Banned authors and Under Review authors generate more views than active authors.
3. While there are almost an equal amount of videos tagged with a Claim and Opinion status, those tagged as a Claim have the majority of views than Opinion tagged videos.
4. Like, Comment and Downloaded count analysis shows that virality is playing a role as even those most videos are on the lower ends of engagement, those that become viral have an impact.

Further analysis that could be done is to analyze the correlation between those who are verified against their claim status and author banned status.
