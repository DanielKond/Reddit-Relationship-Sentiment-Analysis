# Reddit-Relationship-Sentiment-Analysis

Scraped reddit posts from r/relationsips, r/relationship_advice and r/AmITheAsshole using PRAW. Used regex to approximate which posts were made by men and which were by women, and also which could be flagged as relating to abuse or cheating in a relationship. Used Vader for sentiment analysis of the top commenters for those 4 post types.

Results:

There does not seem to be a difference in reactions to commenters concerning abuse and cheating. If such a difference does exist, it appears that top responders are more sympathetic to people who were cheated on than abused.

There also does not seem to be a major difference in reactions to posts made by men or by women. If there is, it appears that mean are treated a bit more negatively and women are treated a bit more positively.


Next steps would include gathering more data, being more careful with the regex and vader code, and segregating the data in order to avoid a possible Simpsons paradox.
