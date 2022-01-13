
# Email spam detection.

Spam detection is a binary classification problem.
By detecting unsolicited and unwanted emails, we can prevent spam messages from creeping into the user’s inbox, thereby improving user experience.

![1_hsyCZOYoGrX6BJsj4Lgrhg](https://user-images.githubusercontent.com/95433685/149326144-c8f86795-bd24-40e4-8043-237df4bdc1db.png)

## Goal.

To classify an email into the spam or not spam.
## Dataset.

1.the dataset has 5592 samples of which 12.63% are spam.

2.we have to predict the target feature.
## Exploratory data analysis.

1.the dataset has 87.37% not spam and 12.63% spam messages.

![download](https://user-images.githubusercontent.com/95433685/149319028-d62a3d8a-1e90-49b9-808f-86bc32a21e6c.png)

2.creating new features that would help in getting a better understanding of the data.

3.from the statistics of this new features , we can observe 
that ham messages have less characters and words compared to 
spam messages.


## Data preprocessing.
1.converting words to lowercase.

2.removing special characters.(such as #, %,&etc)

3.removing stopwords:
stopwords are words that are so commonly used
 that they carry very little useful information.

4.removing punctuations.
(question mark, exclamation point, comma, colon, semicolon, dash etc)

5.stemming.
stemming is breaking down words to thier base form.
such as dancing becomes danc.

6.creating a column after all of this data preprocessing has been done.
(transfrom_text).
## Visual representation.

1.visual representation for most common words used 
in spam messages

![download](https://user-images.githubusercontent.com/95433685/149320779-1fc14692-61e2-4390-a0dd-fde2c6de4485.png)


2.visual representation for most common words used 
in ham messages.

![download (2)](https://user-images.githubusercontent.com/95433685/149320613-c8c64d19-50ea-4d47-b636-dc295cfcdc26.png)


## Model Building.

CountVectorizer :
breaking down a sentence or paragraph or any text into words.

creating dependent and independent variables.

splitting the data into train and test.

Using Naive bayes classifier.

Trained the model on gaussian, multinomial and bernoulli
naive bayes classifier.
## Results.
1.Gaussian naive bayes had the  accuracy of 87.42%
and precison of 51.57%

2.Multinomail naive bayes had the  accuracy of 96.51%
and precison of 84.00%

3.Bernoulli naive bayes had the  accuracy of 97.09%
and precison of 97.37%


