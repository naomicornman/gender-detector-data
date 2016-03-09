
#Gender Analysis of Donald J. Trump's Campaign Finance

##Introduction
Presidential Candidate Donald J. Trump said he will not be beholden to special interests because he was self-funding his campaign. By the end of 2015, Trump's personal contribution accounted for more than half of his campaign financing. However, Trump is not fully self-funded, accepting $7 million in donations. A significant amount of this money comes from individual contributions. We will look at data from the Sunlight Foundation to take a deeper look into these contributions. 

##Methodology and caveats
The source of the data: [Sunlight Foundation, Influence Explorer](http://realtime.influenceexplorer.com/candidate/2016/trump-donald-j/P80001571/)
The data contains information on 5625 contributors. The CSV includes details such as first name, last name, address, city, state, zip code, amount donated, contribution aggregate, employer, and occupation. 
To classify gender, I will use the detect_gender() function. For all names with suffix or middle names or other keys non-detectable by the detect_gender() function, I will use extract_usable_name(). 
This data only shows contributions from individual donors. PAC donations are not accounted for here, and while Trump receives significantly less PAC donations, there still contribute to campaign financing. 

##Past research and articles
- [Information on PAC donations to the Trump campaign](https://www.opensecrets.org/pres16/contrib.php?cycle=All&id=N00023864&type)OpenSecrets.org
- [Is Donald Trump self-funding his campaign? Sort of](http://www.politifact.com/truth-o-meter/statements/2016/feb/10/donald-trump/donald-trump-self-funding-his-campaign-sort/), PolitiFact
- [Which Presidential Candidates Are Winning the Money Race](http://www.nytimes.com/interactive/2016/us/elections/election-2016-campaign-money-race.html?ref=first-draft), New York Times
- [The $7.5 Million in Donations Helping Trump's 'Self-Funded' Campaign](http://abcnews.go.com/Politics/75-million-donations-helping-trumps-funded-campaign/story?id=37403906), ABC News
- [Donald Trump may need a lot of rich backers after all](http://finance.yahoo.com/news/donald-trump-may-need-a-lot-of-rich-backers-after-all-154715815.html), Yahoo News
