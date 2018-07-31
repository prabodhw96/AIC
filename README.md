# Accenture Innovation Challenge 2018
## Pro-ISIS fanboys network analysis and attack detection through Twitter data
### Challenge
Terrorism becomes more severe these days, especially the attacks sponsored by Islamic State of Iraq and Syria (ISIS) or Daesh. They are experts of using social network for propaganda and recruitment, thus predicting their activities through big social network data will help to predict and avoid more serious attacks.
### Solution
We will analyze over 17k Twitter records of pro-ISIS fanboys over a year. Based on those tweets, we want to dig out: 
1. Who is the most important and active member in the social network? 
2. What are the hashtags they frequently used for propaganda? 
3. According to the twitting peak time and information on-hand, will it be able to predict the next attack? 
Our results will reveal the leader in this propaganda network, and achieve a satisfactory attack prediction via time-series neural network through very limited attack history.
### Impact
The development of counter-terrorism technologies must be seen in the context of global counter-terrorism efforts. The objective of our proposed idea coincides with international humanitarian law (IHL) over the need to protect civilians from attack. Terrorism increases uncertainty, which raises the cost of traded goods, especially relative to similar goods produced in a terrorism-free country. Terrorism can divert government expenditures from more productive public investment to less productive security activities. 

As for the future, even if pro-ISIS support moves onto the dark net where open access is not possible, or if a new entity beyond ISIS emerges, our results should still be relevant. The mechanism we’ve identified and theory we’ve developed appear to capture a basic process of human online behavior. Going forward, it can be used to help describe not only pro-ISIS online activity, but also that of any future extremist group or organization.
### To-do List (We're working on it!)
- [x] Data Exploration and Visualization
- [x] Network Graph
- [ ] Attack Detection using Generalized Regression Neural Network
- [ ] Attack Prediction using Time Series Neural Network
### Description of Files
* ``ISIS.pynb`` shows time series analysis of tweets.<br>
* ``ISIS in Social Media.pynb`` depicts the top 10 contenders in the dataset, related tweets over time and relation between tweets and attacks for April 2016 as an example.<br>
* ``Social Cluster Analysis.ipynb`` show social network graph based on Twitter usernames and their respective followers and retweets. *The scale of the node will be influenced by the a combination of the number of followers and the number of tweets they produce*.
#### Associated Visualizations
[Total tweets by ISIS terrorists](https://public.tableau.com/profile/prabodh.wankhede#!/vizhome/TweetsbyUserISIS/Sheet2)
<br>
[Average followers per username associated with ISIS on Twitter](https://public.tableau.com/profile/prabodh.wankhede#!/vizhome/ISISUsernameFollowers/Sheet1)
### Future Scope
We look forward to extend methodologies used in this project to address the problem of henious crime of premeditated extrajudicial killings by group (mob lynching) in India.
### Team Members
* Rohit Singh
* Prabodh Wankhede

**Referred by:** Jasvinder Chhabra (jasvinder.chhabra@accenture.com)
