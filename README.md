### Re Ranking the Power 100
Wilson Hartnell, together with Electionista launched the #Power100 ranked list of political influencers on Twitter. See the press release here: http://www.wilsonhartnell.ie/company-news/launch-wilsonhartnell-power100/

In previous work, http://arxiv.org/abs/1206.1728 a Twitter List Recommender System was built in partnership with Storyful. For details of how the rankings are derived, see the paper.

Below, you will find a re ranked Power100 list, together with a larger, expanded one created by the system.

### Data
The expanded list is available here: https://twitter.com/IgorBrigadir/lists/power100-redux

If you like Network Analysis, various follower, retweet, mention graphs are available in gexf format. https://github.com/igorbrigadir/power100-redux

In total the system processed: 5,959 Users, 29,978 Twitter Lists, 185,214 recent tweets. More data can affect rankings significantly, Twitter API limits slow things down. We can, and will gather more in time.

### Rankings Explained:
The system is designed to expand existing lists, so it attempts to find users most similar to the ones provided. Ranking users is more of a side effect of the recommendation process, rather than the main goal of the system.

Naturally, this list is biased towards politicians. Rankings are based on multiple views of the network of twitter users. A high rankings do not necessarily translate to higher "influence". A better way to do this would be to segment twitter users into communities (TDs only, journalists, commentators, advocacy groups etc).

### Power 100 Redux:
The Original Power 100 List of 200 twitter users, re ranked using our system: http://igorbrigadir.github.io/power100-redux/power100.html

The Expanded Power 100 List of 1024 twitter users, ranked using our system: http://igorbrigadir.github.io/power100-redux/power100redux.html

### About:
Not officially by, but created at: the Insight Centre for Data Analytics, a joint initiative between researchers at Dublin City University, NUI Galway, University College Cork, University College Dublin and other partner institutions. Insight brings together more than 200 researchers from these institutions, with over 30 industry partners, to position Ireland at the heart of global data analytics research.

Better ways of doing this are currently in the works. If you are interested in working with Insight, get in touch: http://www.insight-centre.org/working-with-us

### Disclaimer:
I threw all this together in a few hours in between other work. Updating as I go. Rankings may change with more data crawled!
