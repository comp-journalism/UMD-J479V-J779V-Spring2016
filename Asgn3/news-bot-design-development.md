**Assignment #3 - News Bot Design & Development**

**Out:** February 29, 2016  
**Due:** March 23, 2016 (10am)  

**Overview**  
In this assignment you will design and develop a News Bot for Twitter. The goal is for you to think through what journalistic aims a news bot could accomplish on Twitter and connect that with what is feasible for you to implement in a real functioning bot. 

**Design**  
For some inspiration you might start by [reading about the development](https://source.opennews.org/en-US/learning/automating-transparency/) of the [@CongressEdits](https://twitter.com/congressedits) bot. You can also review the [News Bots paper](http://www.nickdiakopoulos.com/wp-content/uploads/2011/07/newsbots_final.pdf) by Lokot & Diakopoulos for design ideas. And you can peruse a [news bots list](https://twitter.com/ndiakopoulos/lists/news-bots) to give you a sense of what's been done before. 

Initially you should brainstorm some options for bots by considering the dimensions of inputs, outputs, algorithms, and intents. Think about what inputs the bot might have (where would you get that data?), what the outputs would be, whether it will be an interactive bot (will it respond to others?), and overall what it should *do* and why. 

Here's an overview of the design space, though you should feel free to step outside this framework to accommodate new ideas you may have:

<img src="https://github.com/comp-journalism/UMD-J479V-J779V-Spring2016/blob/master/Asgn3/newsbot-design.png" width = "600">

**Implementation**  
As you consider what bot you want to create, you should think about the feasibility of the implementation, including:
- Will your bot hit any rate limits: https://dev.twitter.com/rest/public/rate-limiting
- Will your bot run afoul of the Twitter automation guidelines: https://support.twitter.com/articles/76915 (e.g. please make sure you are not spamming other users on Twitter!)
- Will your bot run in a reasonable amount of time
- Will your bot have access to the inputs/data that it needs

You will find it helpful as you consider feasibility to review the [Tweepy tutorial](https://github.com/comp-journalism/UMD-J479V-J779V-Spring2016/blob/master/Weekly/Week_5/Tweepy-skeleton.ipynb) to refresh your memory of basic Twitter capabilities for e.g. tweeting, searching, or looking at trends. You should also review that tutorial for details on how to create a twitter account, app, and get the necessary keys and tokens to be able to make your bot programmatically tweet. 

To get started with the implementation download the [skeleton Jupyter Notebook ](https://github.com/comp-journalism/UMD-J479V-J779V-Spring2016/blob/master/Asgn3/bot-skeleton.ipynb)for the assignment which includes functions that will greatly simplify your development. You can flesh out the editorial logic of your bot by filling in code in the sections marked as "TODO" in that skeleton notebook. 

**Transparency**  
As part of the write-up explained below you should describe what information you can make transparent about how your bot functions. The goal of journalistic transparency is to develop trust with the public by providing information that allows them to assess the validity and reliability of the journalism. 

For an articulation of dimensions you can consider making transparent about your bot please use this article as a guide:
- [Towards a Standard for Algorithmic Transparency in the Media](http://towcenter.org/towards-a-standard-for-algorithmic-transparency-in-the-media/). 

**Submission**  
This is an individual assignment and you may NOT work in groups. All work should be your own. If you find and use code snippets online that is fine, but you should clearly note this and include a comment with a url link to the original source. 

Your deliverables for the assignment include the .ipynb file which will run the bot, and a written report. The report should describe the editorial intent of the bot and the steps that the bot takes in transforming its inputs to outputs. What do you hope the bot will accomplish given the way you’ve designed it? What are alternatives to the design that you’ve considered? Your report should also describe what you can or ideally should make transparent about the bot and the way it works, what the public should know about your bot so that they can trust it. It should describe relevant information with rationale of why you think the disclosure of that information is pertinent.

You will be evaluated based on your Jupyter notebook (clear and easy to follow, well-commented and structured, adequate documentation), the written report (clear and easy to follow, describes motivation and intended goals and outputs of bot, reflections on challenges of assignment, describes a comprehensive set of transparency information, argues why some info is or is not disclosed), the newsworthiness of the bot (is it goal-oriented, does it address a real news or information need, does it have public interest value), and the functionality of the bot (does it work, does it use computing in a non-superficial way). 

Your should submit (1) your write-up as a .pdf, and (2) your .ipynb file so that your bot can be re-run. 

Mail the .pdf (filename of ASGN3_\<your lastname\>.pdf) of your write-up, and the .ipynb (filename of ASGN3_\<your lastname\>.ipynb) to Professor Diakopoulos: nad@umd.edu by the due date. 
