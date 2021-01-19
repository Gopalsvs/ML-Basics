# ML-Basics
ML Assignment 1 - Question Explanations
NOTE: We expect every question to be answered with some explanations along with the
code/plots. Just the code/plots without suitable explanations would be considered a
partial answer and graded as such.
1) Alcohol Consumption:
1.1: Try to use different visualization techniques and try to see which features have a significant
impact on grades. You can choose two or three features of your choice to do so. For this
question combine all three grades into one may be by taking mean of the grades or any other
way. Request to follow the announcement:
https://ai511discussionforum.slack.com/archives/C019AACP12B/p1601666911101700
1.2: There are different encoding techniques(like Label Encoder, Binary Encoder, Ordinal ..). We
want you to explore different encoding techniques and tell what and all features require
encoding and which encoding techniques you will use for each feature.
1.3: How family relation(famrel) and parents cohabitation(Pstatus) affect grades of students
For example try to see how the grades of students are if their parents are separated and living
together and try to see if that affects the grade of the student. Or just combine and come up with
a new feature, if you think certain features can be clubbed together to give a better analysis,
then the second part of the question would be followed by encoding, do you find the need to do
and if so which columns and how.
2) FIFA 2019:
2.1: Here “economical” is subjective and depends on the metric you choose so try to explore
different possibilities. We want you to derive your own meaning of economical club for yourself.
Data manipulation and being able to make a new feature, basically get used to pandas to make
inferences
2.2: This is a mixed question. Consider it to have 3 parts. First, you need to estimate how “Age”
and “Potential” are influenced by each other. Second, you need to figure out how “Age” changes
the “Value” associated with a player. Finally, you need to plot, for any 10 players of your choice,
their “Age” when they exhibit maximum “Pace” in their career.
2.3 and 2.4: In general we would have certain intuitions as a human that so and so features will
definitely help in deciding the wages or the potential. We want you to test those intuitions using
the data provided and report your findings, not just the ones that proved right but also the ones
that failed. Essentially mention all intuitions you have in this regard and either support ordisprove them using some visualizations on the data. For example, you can use a corr matrix
along with distribution plots (scatter, bubble etc) to qualitatively tell us about your hypothesis.
2.5. Rather than plotting, you could use groupby followed by describe and a few more
conditions to figure this out or you could use a threshold/bins of ages.
3) Accident Data:
3.3: Day of the week means (Monday, Tuesday,.... Sunday), what was the speed limit on the
roads the accidents happened? The intuition behind the question is of feature extraction
(date->day), getting familiar with groupby and whether being a weekday or weekend affects the
speeds. One step further: you could look at not just the highest but the mean or median too.
3.4: In general, our intuition says that bad weather conditions or dim street lights will lead to
more accidents and their severity would be high as well, but does the data say that too? Hint:
Look at each feature separately. Don’t make a new hybrid feature. It can be a scatter
plot/bubble plot/carefully combined and categorized histograms/ any of the frequency related
plots which are in a human understandable form. Please explain your inferences in explanation
below your code.
3.6: This question is a continuation to Q.3.5.
Logistic Regression is in tended for binary (two-class) classification problems. It will predict the
probability of an instance belonging to the default class, which can be snapped into a 0 or 1
classification but how will you do it for three classes? Extending the question, Use
sklearn.cross_validation for doing a CV = 5. The goal as mentioned in the question is not to look
for higher accuracy/hyperparameter tuning (that will become an assignment in itself) but to be
able to identify the preliminary training features and being able to do a multiclass problem using
Logistic Regression.
