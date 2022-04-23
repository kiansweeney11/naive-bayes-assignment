## Question 3 Folder overview

Command used to extract data: **tar xf review_polarity.tar**

Within these extracted folders we have our data and some scripts I ran to help this process.

In the **txt_sentoken** folders I have jupyter notebook files called:

**pos(or neg)-test(or training)-files-labels.ipynb**

The same script was run in the 4 folders. Here is what the code looked like each [time](https://gitlab.computing.dcu.ie/sweenk27/nlp-assignment1/-/blob/master/question-3/txt_sentoken/neg/test-neg/neg-test-files-labels.ipynb)

These files contain the cleaning process to extract the text from all the files in the specific folder
they are in and assign the corresponding labels, positive being 1 and negative being 0. These scripts are all the same for the four folders namely:

- folder for positive test reviews (CV900 or greater files)
- folder for negative test reviews (CV900 or greater files)
- folder for positive training reviews (CV < 900 files)
- folder for negative training reviews (CV < 900 files)

CSV files containing our cleaned outputs are also in these folders and are used in the main script we run assignment1-q3.ipynb which is where our classifier is developed and run.

### Running the files
To run our Naive-Bayes polarity script simply clone this repo and run the aforementioned assignment1-q3.ipynb script.
