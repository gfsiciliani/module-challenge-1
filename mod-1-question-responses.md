# Module 1 Challenge: Question responses

## Q: Given the provided data, what are three conclusions that we can draw about crowdfunding campaigns?

1. Journalism and theater represent a disproportionate portion of data points. These categories also represent the highest success and failed total campaigns.
2. The range of 20,000 - 35,000 as a goal produced the highest percentage of successful campaigns. 
3. The definition of success is relative to each campaign which makes the data quite nuanced. What one campaign with a high goal may consider to be failed, another may consider as profoundly successful.

## Q: What are some limitations of this dataset?

At the time of writing, the most recent point of information in this dataset is nearly four years of age. The categories also represent mostly uncontrollable factors.

This dataset contains basic categorizations and lagging indicators of success. We end up being able to measure commonalities of popularity. This is helpful in understanding trends, though I do not believe we have enough information to to predict and anticipate future trends.

As a creator, I see this list and see categories measuring what I cannot or would not wish to change. In order to analyze what makes a crowd-funding campaign successful, I wish to know information that may focus on quality of the campaign; number of photos, presence of a video, number of tiers of backer rewards, and statistics of backer and campaign admin engagement are categories I think are plausible to knowable and are missing from this dataset.


## Q: What are some other possible tables and/or graphs that we could create, and what additional value would they provide?

### Outlier analysis of most popular categories; theater and plays 
<br>
As I concluded above, the total amount of crowd-funding campaigns that are categorized as theater and plays vastly outnumbers the other categories. I think it would add value to see more analysis into measurable data which the platform and artist alike are able to control and influence. 

Assuming the common goal of a crowd-funding platform and its users is to achieve success, it would be in both those parties best interest to be aware of potential links between success and campaign length (`deadline` - `launched_at`). I believe this would be best represented as a bar graph with success count on the y-axis and the length of campaign representing the x-axis.

Furthermore, the link between success and the presumably highly influential factors of platform promotion (documented as `staff_pick` and `spotlight`) would be valuable for platform awareness of how much their promotion influences success, and for the user to know the potential value of pursuing and influencing such promotion. Again, a bar graph here would make most sense showing success count on the y-axis with x-axis showing six categories; `staff_pick: true`, `staff_pick: false`, `spotlight: true`, `spotlight: false`, `both true`, `both false`.
 
## Statistics of backer count and outcome

### Mean or median
The median represents the bulk of both successful and failed campaigns more fairly than the mean. The distribution of backer count on the upper end is less concentrated than that of the lower end, which makes the median more indicative of a fair central tendency.

### Variability analysis
There is more variability amongst successful results with a standard deviation of 1,267 while that of failed is 961. This makes sense considering there are 565 successful vs 364 failed campaigns. More successful data points produces a higher probability of more variability. Additionally, it makes sense given that the failed outcome represents outcomes bound by a range of numbers (`x`-`goal`) versus a successful campaign being measured only by one bound; minimum. This open ended upper bound results in the range of backers of successful campaigns (16 - 7295) with both a higher mean and median than that of failed campaigns.












