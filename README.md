# SteemBotAnalysis
Steem.js application to analyse the time difference between upvote time of the bots vs posting time.
#### Scope of the project
[SteemBotAnalysis](https://botanalyse.neocities.org) is a website build in HTML - JavaScript using steem.js API.
The main function of the project is analysing the steem data to perform:
* Make a daily analysis of the upvote bots - Find the timing difference between upvote time and post time.
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1516053899/zsfardnuzbtqxdbr3mdg.png)

This will help analyser to understand the user behaviours of the bots, how much time before the pay out date mostly users are using upvote bots.
* List the posts that are upvoted on selected date to deeply analyse user by user and post by post the difference between upvote time and post time.
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1516053982/rtzjaueyrv7xnesxtlxt.png)

#### Using the website
* Clicking on the bot selector, user can choose a predefined upvote bot or enter a bot name by selecting other to analyse.
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1516054440/zhm2j8wucszccpqlpscb.png)
* Clicking on the date selector user can select a date of analysis for the selected upvote bot
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1516054575/h4yrzovcshvsrjcomyn7.png)

* Pressing "START ANALYSIS" button connect to steem api and starts getting data from steem.
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1516054669/c9mps4lv6zjsnh4mhrvd.png)
* After the HTML field is *totally filled* ( this is important and it will take some time ! ) user can press "CALCULATE" button to see result of analysis.
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1516054797/fjbn1rkhilgxqsklb9ui.png)
 * Pressing "CALCULATE" button will give the analysis summary in the boxes.
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1516054888/q4hfrt0bij1jjuydkc7l.png)


#### Technology
HTML and JavaScript is used as programing language.
Google Web Designer is used for design of UI.
Since it is a single page website, there is only [index.html](https://github.com/firedreamgames/steembotanalysis/blob/master/index.html)
The code that is doing the work is : 
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1516055870/vrdumfpycuw5rkzjln0h.png)
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1516055911/tnsgi6jeyjjucjc2drnx.png)

Then to analyse all data, the script reads it back from innerHTML and splits it to the arrays.

Since the steem API calls are asynchronous functions, to convert them into synchronous this (in)genious way is used. 


#### Roadmap
With the development of Steem, the use of upvote bots are also increasing.
* Use this tool to issue daily bot usage analysis results
* Develop script so that it can calculate not daily but weekly or monthly results ( with current tec.used it is not possible )
* Open task requests to perform the analysis with asyncronous functions.
* Website is experimental with free domain. If usage increase carry it to a reserved domain.


#### How to contribute
Task requests will be opened for :
* User friendly interphase
* Array calculations with asyncronous functions in the loop ( API calls )
* Much efficient algortihm for weekly and monthly analysis

#### Changes 18.01.2018
Clickable hyperlinks to the post div. is added. Now user can click the link to reach the post.

