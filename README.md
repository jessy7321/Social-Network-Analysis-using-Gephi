# Social-Network-Analysis-using-Gephi-and-Python
**Outline:** This project aims at Visualization and Analysis of Real-time Twitter data to identify Depressed Users.

**DETAILED DESCRIPTION:**

**Motivation:**
The number of Social Media users is increasing exponentially. Along with this, we see a wide variety of behaviours exhibited by the users - while some are frenetic, others may convey anxiety and poor mental health through their activity - only a couple of the lot. In 2016, the world saw the surge of the popularity of a game called Blue Whale, which made its players to go through a series of self-harming acts and finally resort to suicide. This resulted in a sudden increase of deaths of many, specially teenagers, who fell prey to it. All of their activity was posted on Twitter and other platforms, but no one took action. If they had, it would be a different story. Now that we have sufficient tools to analyze social media activity (in technical terms, "Social Network Analysis"), we must incorporate these features into our social interaction platforms in order to avoid such catastrophic events in the future. One must note that this does not, in any way, call on using private data of users but only get an overview. Misuse of user data or display of information without consent in the name of analysis is not the aim of this project, nor is it encouraged.

**Tools used:**
1. Gephi: Gephi is a visualization tool. Here you can import datasets of a wide range of supporting formats (including CSV) and visualize them as graphs; where the nodes are users or webpages, and the edges are the connections or links between them. After that, you can apply algorithms and study the graph to draw insights. There are other Social Network Analysis tools as well, but Gephi has a much user-friendly workspace (according to me though).
2. Python: Python language is also used to write code for the algorithms. 
(There are certain things where one tool might be insufficient, hence both are used for complete analysis.)

**Dataset used:** This project uses real-time Twitter data. That is, using the Twitter API, actual data of Twitter users is imported into Gephi workspace (The loading of the full dataset according to parameters and filters may take a lot of time). This data can be accessed only by applying for a "Twitter Developer" account and being approved. If you have any other network dataset, it will work perfectly fine. Since, this project aims as detecting anxious and/or depressed users, I suggest you to try applying network data of users on any social platform.

**Measures considered and respective algorithms:**
1. Community detection - Girvan Newman Algorithm
2. Homophily - Fatman Evolutionary Model
3. Spatial Segregation - Schelling Model
4. Diffusion
_(Detailed Description of each measure is given in respective code documentation)_
