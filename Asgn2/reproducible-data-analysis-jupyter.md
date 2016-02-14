**Assignment #2 - Reproducible Data Analysis with Jupyter**

**Out:** February 15, 2016  
**Due:** February 29, 2016 (10am, before class begins)  

**Overview**  
The goal of this assignment is to gain experience using the Jupyter programming environment (including Python, Pandas, and Matplotlib) by undertaking a journalistic data analysis of a large government dataset in a way that would allow for reproducibility by others. In particular you'll be analyzing data from the federal government's [College Scorecard](https://collegescorecard.ed.gov/).

**Getting Started**  
You'll first want to have a solid understanding of the in-class tutorials we've done on loading, manipulating, and visualizing data with Pandas. Additional documentation on Pandas can be found [here](http://pandas.pydata.org/pandas-docs/version/0.17.1/)

You should download the [skeleton notebook](https://github.com/comp-journalism/UMD-J479V-J779V-Spring2016/blob/master/Asgn2/asgn2-skeleton.ipynb) provided and open it in your your Jupyter environment. The notebook has links to the dataset you'll use, as well as the full data documentation, and the full data dictionary. There are thousands of variables, and you *really* want to go through the full data documentation carefully before getting started with the analysis. You'll need to reference the full data dictionary frequently in order to understand what each of the variables means and how you might parse it. 

**Details**

It's best for you to look directly in the skeleton notebook for instructions and details but a brief overview is given here. Within the notebook there are five questions that you must answer. After each question, add a cell and write code using Python, Pandas, and Matplotlib in order to arrive at the correct solution to the question. Be sure to include comments in your code! Someone else looking at your notebook should be able to follow your code and your logic in solving the question. The more documentation you provide for your method, the better - make it reproducible!  

After the five questions there is a chance for you to come up with your own data-driven insight. Try to think like a journalist: what can you find in the data that could make for a news headline? 

Then you'll work to "re-create" the first college ranking listed in this [NPR article](http://www.npr.org/sections/money/2015/09/18/440973097/obama-wont-rate-colleges-so-we-did). Pay very close attention to the methodology, but also realize that your final ranking won't be *exactly* like the one published (though it should be pretty close). 

In addition to the notebook which you flesh out, you should work on a written description of your reflections on the assignment (e.g. challenges, difficulties), a description and interpretation of your insight (why is it important?), and the answer to one additional question: Take the ranking you created and think about how you could get the University of Maryland-College Park to rank as highly as possible. Explain how you would go about figuring out the highest ranking that UMD could possibly achieve as a result of using different sets of weights on the input factors to the ranking. Reflect a bit on the validity of college rankings in general: do you trust the rankings presented in the NPR piece?

*EXTRA CREDIT*: For up to 5 extra points (out of 100) on the assignment transform your written explanation of how to optimize UMD's ranking position into code and include that in your Jupyter Notebook. What's the highest position UMD could take? 

**Submission**  
This is an individual assignment and you may NOT work in groups. All work should be your own. If you find and use code snippets online that is fine, but you should clearly note this and include a comment with a url link to the original source. 

You will be evaluated based on the clarity of your Jupyter notebook (easy to follow, well-commented and structured, adequate documentation for reproducibility), the quality of your written report which should include your interpretation and reflection on the assignment (easy to follow, explains assumptions and editorial decisions, interpretations reflect an understanding of the underlying data, reflections on challenges of assignment), and the Analysis Methods (accurate, bug free, makes use of Pandas / Matplotlib / Python effectively, logical, analysis reflects accuracy and understanding of data). 

Your should submit (1) your write-up of ~600 words (excessively short or long write-ups will be penalized) as a .pdf, and (2) your .ipynb file so that your analysis can be re-run.  

Mail the .pdf (filename of ASGN2_\<your lastname\>.pdf) of your write-up, and the .ipynb (filename of ASGN2_\<your lastname\>.ipynb) to Professor Diakopoulos: nad@umd.edu by the due date. 
