# TransportAssignment
An analysis of Irelands transport data- with comparison of another country
Updated CodeBook contains necessary libraries.
It has used html web scraping to gather reviews of a bus service.
A class object was created for data aggregation and some data preprocessing.
Dtypes and date range checked.
The review frequency was plotted.
A new dataframe called topic was created for text analysis.
Additional data preprocessing- removed stop words, unecessary words and emojis.
A single string was created using .join method to display word frequencies.
A word cloud was plotted to visualise most frequent words.
Implementation of a function to preprocess the sentences to have a list of words for each sentence(for topic modelling)
Created a dictionary for Latent Dirichlet Allocation [a generative model] which uses Baysian inference
3, 5 and 10 topics were tested for num_topics- result was quite repetitive. 
An intertopic Distance map was used to visualise topics n=5 for deeper understanding and LDA 
num-topics was set to 1 for plotting the most frequent topic using bar and bubble graphs.
The sentiment scores were calculated for each review and the compound score of each review was added to the df as a column.
Using a lambda expression an additional column was created with poisitve-negative-neutral mapped to the compound score.
A quick test on a Naive Bayes algorithim for classification was implemented and in need of additional data preprocessing, optimization and validation.
