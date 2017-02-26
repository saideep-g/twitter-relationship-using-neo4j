# twitter-relationship-using-neo4j
Visually looking at the twitter relationship(s) using Neo4j and tweepy. This is a very basic attempt and additinal enhancements can be done to reduce noise and present the relationships better to draw conclusions.

# graph in Neo4j
![Neo4j graph](https://github.com/saideepchandg/twitter-relationship-using-neo4j/blob/master/ne04j_graph.png)

# prerequisites

* Neo4j should be installed and running at http://localhost:7474
* pip install tweepy 

# Notes
* attempt was made to stay within the twitter api rate limits; hence ```tweepy.Cursor``` and ```time.sleep()``` is not used
