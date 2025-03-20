# KickStarter_Project

📊 Project Overview
This project analyzes existing Kickstarter campaigns in order to provide viable insights and recommend action steps that raise the chance for the success of starting a Comic campaign. It also provides Machine Learning in order to predict the success or failure of the project, the expected pledge amount, and to predict the percentage of funding of the campaign.

📂 Dataset Information
The dataset contains details on Kickstarter campaigns, including:
Campaign details (name, category, location, status)
Financial data (goal, pledged amount, funding percentage)
Backer engagement (number of backers, updates, comments)
Campaign setup (reward levels, duration, launch date)

🔎 Key Insights
Mean Pledge Amount:
Average total pledge per campaign = $5,065.37
Number of Backers Distribution:
Fewer campaigns have a large number of backers.
The histogram shows that the majority of campaigns have fewer backers, while successful campaigns generally attract more backers.
Success Rate:
Overall success rate = 55%
Success Rate by US State:
Success rate varies across states, with some states performing significantly better than others.
Differences Between Successful and Failed Campaigns:
Top successful campaigns offered rewards starting from $1, whereas top failed campaigns started from $10+.
Successful campaigns had more frequent updates and higher interaction with backers.
Lack of updates correlated strongly with failure.
Influencing Factors:
✅ Number of updates (optimal = 4+ updates)
✅ Lower funding goal increases chances of success
✅ High number of comments = higher success rate
✅ State of launch and deadline month impact success
❌ Duration of campaign had no significant impact on success

💡 Recommendations
🎯 Increase Backer Engagement:
Post at least 4 updates during the campaign.
Encourage interaction by targeting at least 50 comments per campaign.
🎯 Set Realistic Goals:
Lower funding goals increase the likelihood of success.
🎯 Optimize Campaign Setup:
Start reward levels from $1 to attract more backers.
Consider the state and month of launch to maximize exposure and success.

📈 Visualizations
✅ Top 10 distributions of campaign status over the number of updates
✅ Average amount expected to earn in pledges over locations
✅ Median percentage of funding over locations
✅ Effect of duration, goal, percentage funding, and average number of comments on success and failure.
✅ Machine Learning Model results

🏆 Next Steps
Deep dive into category-specific trends.
Analyze time-based trends for seasonal impacts.
Explore potential clustering of successful campaigns based on location and goal.

