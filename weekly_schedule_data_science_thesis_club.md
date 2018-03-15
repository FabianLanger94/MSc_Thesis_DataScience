# Weekly Schedule Data Science Thesis club

# Thesis period

* 2018 meetings are on Wednesday 15:00-17:00 in A.124
	* 	week 1= April 4
	* week 12 = June 20 



## Week 3 Related work

1. Organize your related work section into 3-4 subsections.
2. Indicate which subsection belongs to which (group of) RQ's. (just for yourself , you ca remove that later)
3. You have a starting subsection which simply lists and describes the _state of the art_ regarding your main research question. Roughly 5-10 references, each described in 2-3 sentences.
4.  The other subsections are usually more technical and you use them to describe and refer to technologies and methodologies that you will use for answering your RQs.  
5.  Try to have the related work more or less complete, but you can list it clusterd via bullet points for now

##### Tip
* Use this schema for your citation keys: `nnnn:aaaayy`, where nnnn are the first 4 characters of the first author, aaaa the first four characters of the first non stopword of the title and yy the last two digits of the publication year.
* Save all pdfs in a literature folder and use the same name for the file as that bibtex key. 
* Use markers and notes to annotate the pdfs so you can quickly find the important parts back.
* Write for each article a small synopsis with the 3-4 main points, a short abstract in your own words and 2-3 lines why this is relevant to your research. 

## Week 2 Update on your first full week internally

* Tips and tricks for others
* problems, issues
* Do you now have good access to the data?
* Are all three involved (you and your two supervisors) aware of your research question(s)? Do your RQs mean the same for all 3? Are you sure? How do you know that? 

#### Homework
1. Try to answer each of your research questions in a really stupid way. If you can, you must reword it.
2. For each RQ, provide the _format_ of the answer, and the _form of the evidence_ which belongs to that answer.
	* E.g. RQ: What is the influence of "aggresive feature selection" for my text classification performance? 
	* **Evidence** Typically a graphic in which you vary the feature selection and show the resulting performance.
		* E.g.: number of features on the x-axis, and F1 score on the y-axis
		* Or, a set of precision-recall curves for a number of feature selction settings
		* In a  good case, an optimal value(range) becomes clear from your grahic (so you also have worse performance on both sides).
3. For all of the things that you have done this week, indicate the RQ for which you have done it. If there is none, stop doing that , or simply create the appropiate RQ ;-)




## Week 1

1. Describe your data as well as possible:
	* X- variables and y-variables
	* what data types are the individual variables
	* is the data "raw" (direct observation) or derived?
	* Missing values and what do you do with those missing values?
	* Plot distributions of the values per attribute/column (`sns.distplot`)
		* Normally distributed
		* Skewed
		* ...
	* Possibly find correlations (think of `sns.pairplot`)
	* process from raw data to data in the format of your X matrix
	* what do the individual variables **mean**
	* Size: in Gb, in number of rows, columns (if text, size of vocabulary)
2. What is the task you will perform on this data?
	* Regression, classification, visualisation/organising, ...
	* What normalization is needed? Missing values? 
	
##### Output: Exploratory data analysis notebook on your github
* Useful Example: <https://www.kaggle.com/ekami66/detailed-exploratory-data-analysis-with-python>


<hr/>