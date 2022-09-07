We worked on project in which we were provided with data of PSL players. Our task was to select 16 men squad for  T20 team of Pakistan. we were provided with
unlabeled data so we decided to performing unsupervised learning (K-means clustering) on both batsmen and bowlers. Following are the steps which will 
help you to understand what we have done. 


1.) First we have performed clustering on "batsmen.csv" (clustering was performed on batsman's "innings", "strike rate" and "average") and "bowlers.csv" 
(clustering was performed on bowler's "economy", "strike rate" and "average").

2) After performing clustering we created "batsmenLabel.csv" and "bowlersLabel.csv"

3.) Then we performed analysis for batsmen and bowlers which can found in jupyter file named, "analysisForBatsmen" and "analysisForBowlers".

4.) After performing analysis for bowlers and batsmen, we created csv file for selected batsmen and bowlers namely, "batsmenSelected.csv" and "bowlersSelected.csv". 
we selected 9 batsmen and 7 bowlers.

5.) We also performed decision tree classification which is supervised learning technique on files, "batsmenLabel.csv" and "bowlersLabel.csv" so that we can predict 
the class of player by entering his "strike rate", "average" and "innings".  