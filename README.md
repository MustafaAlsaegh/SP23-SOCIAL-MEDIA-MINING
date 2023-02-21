## Social Media Mining 


### Content Analysis [Fur or Faux?] Explanatory Approach for Pro- and Anti-fur users in Reddit.

#### Introduction
This project analyzes user sentiment and advocacy towards animal fur on Reddit. We examined user comments on pro-fur and anti-fur subreddits to identify differences in the language used by each group. We also analyzed users' interactions in political subreddits to understand the relationship between political views and advocacy towards animal fur. Finally, we explored the relationship between users' gender and advocacy towards animal fur.

##### 1. Reddit content Analysis [Comments extraction and visual].py

This file is used to extract the comments from the pro-fur and anti-fur subreddits as well as it calculates the word frequency of the comments in the pro-fur and anti-fur subreddits.
It takes the following parameters:
subreddit_name: The name of the subreddit to be analyzed.
post_count: The number of posts to be analyzed.
comment_count: The number of comments to be analyzed per post.


##### 2. Finding_User_interests.ipynb

This file is used to analyze the political views of Reddit users. It also takes the following parameters predict the gender and interests of Reddit users.
The code categorizes the users as either liberal, conservative, or unidentified based on their political engagement. The categorization is done by counting the number of comments a user made in each of the political subreddits and comparing it to a threshold value. If the user has made more comments in subreddits that are classified as liberal or conservative, they are categorized accordingly. If they have not interacted enough in these subreddits, they are classified as unidentified.
It takes the following parameters:
subreddit_name: The name of the subreddit to be analyzed. ex r/conservative, r/liberal, r/womenrights, r/askmen
post_count: The number of posts to be analyzed.
comment_count: The number of comments to be analyzed per post.


#### Results

The analysis showed that pro-fur users tend to use positive language, while anti-fur users use more negative language. Additionally, anti-fur users tend to have more interactions in political subreddits and are more likely to be classified as liberal. Finally, the analysis of gender and advocacy towards animal fur revealed that there is no significant relationship between the two.

#### Limitations

The scope of this research is limited as it only examines user comments on the fur topic and includes a limited sample size of posts from a particular time frame. As a result, the findings may not be generalizable beyond this specific group. Therefore, more extensive research is required that expands the scope and enables a comparison of similar types of thinking from different social media platforms.

#### Conclusion

The analysis provides valuable insights into the user perspective on animal fur on Reddit. Further research can be done to expand the scope and enable a comparison of similar types of thinking from different social media platforms.
