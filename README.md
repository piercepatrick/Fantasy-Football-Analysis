# Ryan Tannehill Fantasy Football Performance: Project Overview
- Built a linear regression model that predicts fantasy points from passing touchdowns within 22 points
- Generated a probability distribution which displays the probability of scoring a passing touchdown when a team is X Yards Away from the Endzone to calculate expected passing touchdowns for each quarterback in the 2019 season.
- Created a Dot Plot Distribution Visualization to show how Tannehill faired among relevant Quarterbacks.
- Leveraged data for fantasy football from the 1970-2019 seasons and play by play data from 1999.
- Engineered features relevant to fantasy football.

# Resources Used
**Python Version:** 3.7  
**Packages used:** pandas, numpy, matplotlib, sklearn, seaborn  
**Tutorials:**   
https://www.fantasyfootballdatapros.com/
https://www.machinelearningplus.com/plots/top-50-matplotlib-visualizations-the-master-plots-python/  
**Obtaining Play by Play Data:**  
https://colab.research.google.com/drive/1xZVqYc-nkGTZAVFx9tpH-cQlQpIcKDwQ?usp=sharing

# Data Cleaning
- Renamed columns Yds, Yds.1, and Yds.2 to PassingYDs, RushingYDs, and ReceivingYDs
- Renamed PPRFantasyPoints to FantasyPoints
- Removed StandardFantasyPoints and HalfPPRFantasyPoints columns
- Made columns for Usage, TotalTD, FantasyPoints/GM, UsageRank, FantasyPointsRank, FantasyPoints/GM_Rank
- Filtered data frames for just quarterbacks

# How did Ryan Tannehill compare to other top Quarterbacks?
<img src="/Tannehill%20Analysis%20Images/dotplotdistribution.png" width='1000'>
<img src="/Tannehill%20Analysis%20Images/tannehillvswilson.png" width='500'>  

# How much did the Marcus Mariota to Ryan Tannehill switch in Week 7 affect the offense's Fantasy Football performance?
<img src="/Tannehill%20Analysis%20Images/ajbrown.png" width='500'>  
<img src="/Tannehill%20Analysis%20Images/jonnusmith.png" width='500'>  
<img src="/Tannehill%20Analysis%20Images/derrickhenry.png" width='500'>  

# Did Ryan Tannehill over-perform in the 2019-2020 season, and is he due for a regression in the 2020-2021 season?
<img src="/Tannehill%20Analysis%20Images/evsapassingtd.png" width='500'>
<img src="/Tannehill%20Analysis%20Images/evsavisualization.png" width='1000'>

# How does Passing Touchdowns affect Fantasy Points?
<img src="/Tannehill%20Analysis%20Images/linearregression.png" width='500'>
