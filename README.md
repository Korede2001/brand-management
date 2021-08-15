# brand-management
Coursework on Strategic Brand Management with strong emphasis on experimentation and hypothesis testing

## Background
As part of a school course, I created a blog brand, [Football Manager Hero](https://football-manager-hero.medium.com/), that teaches players of a soccer simulation video game ([Football Manager](https://en.wikipedia.org/wiki/Football_Manager), herein FM) how to effectively manage lower-league teams.

To grow the brand, I proposed, executed and evaluated growth hacks (aka experiments), leveraging my solid educational background on experimental design and hypothesis testing. This process involved (1) generating a hypotheses (null & alternative), (2) designing an experiment to collect data and test the hypothesis (3) selecting metrics that are aligned with the hypothesis (4) selecting an appropriate statistical test given the data and (5) verifying or refuting the hypothesis

The growth hacks I ran are described below as well their results and key insights from the tests:

### Growth Hack 1: A/B Testing Blog Post Titles on Twitter
---
The treatment title included a digit, following research on the attentional benefit of digits when surrounded by letters (see paper). The control title on the other hand, excluded the digit.

**Key Metric:** Total number of engagements (retweets + likes + media clicks +link clicks + detail expands)

**Statistical test:** Chi-squared test

**Key results:**
- Statically significant difference (p= 0.0342) in engagements between the treatment and the control title, albeit in the unanticipated direction: the control title engaged users more than the treatment title
- Extending to practical significance, however, we find that the increased engagement from the control title is not very meaningful: a weak association was found between the number of engagements and post type (Cramer’s V= 0.0445). Similarly, Cohen’s h (h = 0.11) suggested a minute difference in the engagements between both groups.

**Note:** The contradiction between practical and statistical significance is not surprising given the large sample of 2269 people. This makes it more likely to find a statistically significant difference, despite a tiny effect size.

**Key Takeaways:** Adding a digit to the title did not improve engagement, thus refuting my hypothesis. It instead appeared to reduce engagement, although not to a meaningful degree

### Growth Hack 2: Testing Social media platforms
---
Next, I tested social media platforms (Reddit vs. Facebook) to determine which was more suited for my content-type. In both social media platforms, I targeted FM-specific audiences by posting in FM-groups with a similar number of active users.

**Key Metric:** Total number of engagements (reactions + link clicks + comments)

**Statistical test:** Chi-squared test

**Key Results:**
- The difference in engagements between the two platforms was not statistically significant (p = 0.22), suggesting that the total number of engagements does not (reliably) differ based on the platform posted on (Facebook vs. Reddit).
- Given that the link to the blog post had to be posted in the comment section in Reddit as against the main post, the blog post link had an unfair advantage on Facebook. Not taking into account link clicks, there was a statistically significant difference in the number of engagements in favour of Reddit (p= 0.001). 

**Key Insights:**
- Based on the results, we fail to reject the null hypothesis that there is no relationship between the platform and the number of engagements
- The test was not a fair test (most especially due to the difference in link placement). As such, to be more confident in the result it might be worthwhile to rerun the test and  if possible, for a longer test period.



