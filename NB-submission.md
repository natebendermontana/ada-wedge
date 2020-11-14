
# Applied Data Analytics

## Wedge Project

<!-- Any general commentary you'd like to say about the project --> 

### Task 1

* Files for this task: 

I followed Antonio's lead and uploaded all the clean Wedge files to GBQ manually using the buckets functionality in Google Storage. 


### Task 2

* Files for this task: 
`Task2_Bender_Owner_Sample`: 
Takes a random sample of 450 owners from the overall list of 27,207 unique owners in the data. Then, pulls all associated data with that random sample from GBQ and formats it into a text file with appropriate headers. 
`sample_owners.txt`: 
The text file described above. 

### Task 3
`Task3_Bender_Summary_Tables`: 
Creates summary tables for three different queries of the Wedge data. 
Query 1: extracts sales by date by hour
Query 2: extracts sales by owner by year and month
Query 3: extracts sales by product description by year and month
`Sales_by_Date_Hour.txt`: 
The summary table for Query 1
`Sales_by_Owner_date.txt`: 
The summary table for Query 2
`Sales_by_Product_Date.txt`: 
The summary table for Query 3
`NBwedgetask3.db.zip`: 
Compressed database file containing the three summary tables outlined above. File compressed in order to stay within the file size upload limit for GitHub. 

## Query Comparison Results

Fill in the following table with the results from the 
queries contained in `gbq_assessment_query.sql`. You only
need to fill in relative difference on the rows where it applies. 
When calculating relative difference, use the formula 
` (your_results - my_results)/my_results)`. 


|  Query  |  Your Results  |  My Results | Difference | Rel. Diff | 
|---|---|---|---|---|
| Total Rows  | 85760139 | 85760139 | 0  | 0  |
| January 2012 Rows  | 1,070,907  | 1,070,907  | 0  | 0  |
| October 2012 Rows  | 1,042,287  | 1,042,287  | 0 | 0 |
| Month with Fewest  | Aug 2016  | Aug 2016  | No  | NA  |
| Num Rows in Month with Fewest  | 858,168  | 858,168  | 0  | 0  |
| Month with Most  | Apr 2012  | Apr 2012  | No  | NA  |
| Num Rows in Month with Most  | 1,135,000  | 1,135,000  | 0  | 0  |
| Null_TS  | 7,123,792  | 7,123,792  | 0  | 0  |
| Null_DT  | 0 | 0 | 0 | 0 |
| Null_Local | 234,843 | 234,843 | 0 | 0  |
| Null_CN  | 0 | 0  | 0 | 0 |
| Num 5 on High Volume Cards  | 14987  | 14987  | No  | NA  |
|  Num Rows for Number 5 | 460,630 | 460,630 | 0 | 0  |
| Num Rows for 18736  | 12,153  | 12,153  | 0  | 0 |
| Product with Most Rows  | banana organic  | banana organic  | No  | NA  |
| Num Rows for that Product  | 908,639 | 908,639  | 0  |  0 |
| Product with Fourth-Most Rows  | avocado hass organic | avocado hass organic  | Yes/No  | NA  |
| Num Rows for that Product  | 456,771 | 456,771  | 0 | 0 |
| Num Single Record Products  | 2,769  | 2,769 | 0 | 0 |
| Year with Highest Portion of Owner Rows  | 2014  |   | Yes/No  | NA |
| Fraction of Rows from Owners in that Year  | .7591 | .7591 | 0 | 0 |
| Year with Lowest Portion of Owner Rows  | 2011  | 2011 | No  | NA |
| Fraction of Rows from Owners in that Year  | .7372 | .7372  | 0  | 0 |

## Reflections

<!-- I'd love to get 100-200 words on your experience doing the Wedge Project --> 
I've struggled mightily this semester with all aspects of this course (& my other courses/work) due to the remote learning environment we're forced into by the pandemic. I've performed worse this semester than any other. So my frustration with this project has been high, but it's not been necessarily because of the project itself. 

From a conceptual standpoint, the way this project exposes you to the power of cloud computing with GBQ and the interactivity that is possible between different local/cloud tools like R, SQlite, and GBQ is fairly mind-blowing. I'm still shocked by the ability to query 86 million rows of data in a matter of seconds, for instance. So learning about how these tools can be used together has been a highlight of this project. I've also gained vastly more appreciation for value in data engineering work (and I didn't even have to clean the files like the A students did!)


