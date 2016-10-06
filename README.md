# digital-defender
This is the repo to collaborate on Thorn-Cloudera's project at OSD- GHC16. Please create a folder with your team name, add your work there and submit a pull request.
Here is the project description page: http://systers.org/wiki/communities/doku.php?id=wiki:ghc:ghc16:osd:cloudera

## Data Sets:
Sanitized Chat Data over a few months for 2 chat rooms
```
{
‘author': 'User1',
'content': '@User2 MESSAGE LINK1 ',
'id': u’ef66e354-aa47-42fc-92f3-dcbed2802510',
'scrape_datetime': u'2016-09-06 02:10:31.152588’,
'site': ‘SITE1'
}
```

## Guiding Questions
1. UI/UX
  * Landing page show high level overview: chat room stats, top user table, includes search
  * Views: user profile, content, network analysis
2. Data Insights
  1. Messages over time per chat room
  2. User Stats:
    * distributions by: # messages, # unique links posted
    * Top Users:
    * post patterns, num of original links posted
  3. Content Stats:
    * Most popular content, distribution of content by popularity
    * How often is new content posted?
  4. Network
    * Who talks to who? graph analysis to rank users? do sub communities exist?

## Tools (Need to finalize once we decide on our data hosting and analysis strategy)
Javascript, React, Python (numpy, scipy, pandas, networkx), Jupyter notebooks, git

## Open questions:
1. Which bootstrapping model do we want to choose for data hosting and analysis?
  1. Option 1: Provide the dataset in a downloaded location
    And participants can download, use their favourite tools for exploration and generating stats. Upload the code and insights to github.
  2. Option 2: Hosted on Cloudera infrastructure
    * Create an EDH cluster - Sravya
    * Create Thorn dataset as a Hive table? - Sravya
    * Make sure Spark is setup and we can run spark jobs on this dataset
    * User account setup: Setup cluster accounts for all users.
    * Analysis:
      * Spark shell
      * Hue console
      * Sense
      * Jupyter notebook
    * Preparation before hackathon is strongly encouraged:
      * Get familiar with one of the analysis tools mentioned above.
  3. Option 3: Docker?
2. We do not have mentor expertise in react and javascript
  * Can we get more mentors to fill this expertise gap?
  * If not - shall we remove this project?

## Data Hosting? (Sravya - I am not sure what this is?)
LINK1, FINGERPRINT 1
LINK2, FINGERPRINT 1
LINK3, FINGERPRINT 2
