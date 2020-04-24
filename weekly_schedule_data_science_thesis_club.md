# Weekly Schedule Data Science Thesis club

# Thesis period

* 2018 meetings are on Wednesday 15:00-17:00 in A.124
	* 	week 1= April 4
	* week 12 = June 20 
	
## Week 12 Defense
* Prepare slides
* Give a test presentation
	* for friends/other students
	* at your internship

## Week 11 Thesis finished	

* Hand in 7 days in advance of the defense

	
## 	Week 10 Introduction and Conclusion finished
* See that all parts in your thesis have a functional role in answering a (part of a) research question.
* No problem if you "slighlty"" reword/ reorder/rearaange your research questions at this point.


## Week 9 Results section  finished
* Maybe you need to do some more experiments, but you then have stubs for all the results of those you want to put in.

## Week 8 Methodology section finished
* This is now cryctal clear and you do'n have time to change anything in your methodology anyway, so just record what you have been doing.

	
## Week 7 Preliminary results, evaluation in order

1. Present preliminary results
2. So have a table with evaluation numbers and graphics.
3. Know how you can use all those numbers to answer your RQ(s).

**You probably won't have all results (yet), but you should have your evaluation pipeline in place and you should know how to turn your results into an answer to tyour RQ(s)**	

	
## Week 6 Midterm report and presentation	

#### Finished parts of your thesis

1. Title, abstract, keywords
2. Part of the introduction with the research questions.
2. Related work
2. Description of the data/Experimental setup

#### Skeletons ready

* Introduction
* Methodology
* Results

	
## Week 4/5 Description of the data

1. Finish this (sub)section of your thesis.
2. For the content, see week 1.	
3. This is an easy to write and read section, with nice plots, which should give th ereader a good overview of your data, in terms of size, content, connections between the variables.
4. Keep it connected to your research questions.
5. **Decide** which level of detail you want to include here in the thesis, and which parts you want to put in an Appendix.
	6. Typically you describe the nitty gritty details of data cleaning and decisions about oulier removals etc in the Appendix. 
	7. The level of detail in the appendix should be such that your research can be reproduced starting with the raw data.

## Week 4/5 Baseline ML algorithm plus evaluation

1. Based on the ideas expressed in this blogpost <https://blog.insightdatascience.com/always-start-with-a-stupid-model-no-exceptions-3a22314b9aaa>, create a really simple model from your data. 
2. Think of Principal Component Analysis and (logistic) regression.
3. Use `seaborn` plots to understand your data.
4. Make sure you have a basic ML pipeline in place, including printing some plots which help you understand the workings of your classifier.
	* confusion matrix
	* precision recall curve
	* ..

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

### Related work vs Background

* Sometimes you want to *explain* techniques that you use, referring to the literature. This can go to a *background* section. 
* In the related work you describe how other people have dealt with similar problems as you are dealing with. What were their techniqies, what were their results, what observations did they make that you have used, etc.

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
