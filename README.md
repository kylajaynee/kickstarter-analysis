# kickstarter-analysis
...
## Overview of Project

### Purpose
Visualize campaign outcomes for crowdfunding goals for theater productions based on launch date 
...
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Outcomes Based on Launch Dates](C:\Users\kris\Desktop\Class Folder\Crowdfunding analysis\Outcomes Based on Launch Dates.png)
### Analysis of Outcomes Based on Goals
![Outcomes VS Goals](C:\Users\kris\Desktop\Class Folder\Crowdfunding analysis\Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
Some challenges arose while formatting percentages in the Outcomes Based on Goals project, I set the cells to format as percentages and then divided the count of my desired outcome by the total in that goal range. 
Formatting the `COUNTIFS` functions was difficult when making a goal range. I wrote it out successively as `Kickstarter!$D:$D,">=1000",Kickstarter!$D:$D,"<5000"` to achieve the range of 1000 to 4999. 
...
## Results

### Conclusions

#### What are two conclusions you can draw about the Outcomes based on Launch Date?
- No crowdfunding campaings for theaters that were canceled launched in the month of October.
- May is the best month to launch a crowdfunding campaign for a Theater. 
#### What can you conclude about the Outcomes based on Goals?
- A crowdfunding campaigns for plays with a goal under $5000 is likely to succeed.
- Most crowdfunding campaigns for plays have a goal $1000 to $4999
### What are some limitations of this dataset?
The goals are not standardized making the results difficult to compare
### What are some other possible tables and/or graphs that we could create?
- Compare goal and pledge amounts by country or currency 
- Compare pledged amounts by length of crowdfunding campaign 
