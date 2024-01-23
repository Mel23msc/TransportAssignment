# TransportAssignment
An analysis of Irelands transport data- with comparison of another country<br>
Special considerations- Fair usage as part of academic work, ethically considered by protecting user data involving specifying the div on the web page to only collect the text review and date.<br>
Robot.txt file read- it is understood reviews form a part of the allowed scrapings- <br>
Terms of use- Academic purposes only not for re-distribution, or any uses outside of its original purpose.<br>
Contacted 3rd party for consent and Transparency- awaiting response
<ul> 
  <li>Updated CodeBook contains necessary libraries.</li>
<li>It has used html web scraping to gather reviews of a bus service.</li>
<li>A class object was created for data aggregation and some data preprocessing.</li>
<li>Dtypes and date range checked.</li>
<li>The review frequency was plotted.</li>
<li>A new dataframe called topic was created for text analysis.</li>
<li>Additional data preprocessing- removed stop words, unecessary words and emojis.</li>
<li>A single string was created using .join method to display word frequencies.</li>
<li>A word cloud was plotted to visualise most frequent words.</li>
<li>Implementation of a function to preprocess the sentences to have a list of words for each sentence(for topic modelling)</li>
<li>Created a dictionary for Latent Dirichlet Allocation [a generative model] which uses Baysian inference</li>
<li>3, 5 and 10 topics were tested for num_topics- result was quite repetitive.</li> 
<li>An intertopic Distance map was used to visualise topics n=5 for deeper understanding  </li>
<li>LDA num-topics was set to 1 for plotting the most frequent topic using bar and bubble graphs.</li>
<li>The sentiment scores were calculated for each review and the compound score of each review was added to the df as a column.</li>
<li>Using a lambda expression an additional column was created with poisitve-negative-neutral mapped to the compound score.</li>
<li>A quick test on a Naive Bayes algorithim for classification was implemented and in need of additional data preprocessing, optimization and validation.</li>
</ul>
