# Video-Games-Reviews-Capstone

This is a research project centered around data cleaning, visualizations in the forms of graphs and tables, and using statistical methods such as t-tests to detect and present the difference between user and critic scores for video games. 

It is the goal of this research to see if there is indeed a statistically significant difference between these scores, and to map it in such a way that anyone can understand it. The video game industry was once dominated by a handful of critics and companies who often would make or break a game's success based on their reviews. Today, platforms like YouTube and Metacritic offer a way for the players themselves to rate games. How much have the times changed? What kind of differences exist between these scores? Are critics perhaps being paid off to give games favorable reviews?

After finding an aesthetic image as a cover page and loading up the data, I delved into the data exploration process. I used my knowledge of python and pandas to extract various bits of information out of the database. How long did these records go back? What kind of datatypes was I working with? How many units were sold per game? With the answers to these questions, it was necessary to manipulate the table in such a way as to make my job easier. I added and removed some columns so that I could more easily analyze the data. It also became apparent that it would be more effective to use the t-testing method if I broke the data into two groups- games that sold over 10 million units, and games that did not. Doing this meant a statistical analysis of two variables instead of three- much easier!

After cleaning the data, I went ahead and created many relevant and aesthetic graphs to present my findings. The graphs included the numbers of units sold for all games, the user and critic scores for these games, the differences between the scores, and more. I found bokeh hvplots to be a wonderful tool in achieving accurate and good-looking results. 

Finally, I did t-tests to test for statistical differences between the scores. What I found was that there were indeed significant differences between scores, and that games have always been overrated by critics compared to users. Specifically, the Call of Duty franchise had the top 5 most overrated games, with extreme differences in scores!


This project is meant to be read through Google Colab so that Bokeh hvplots works!
