# About Dataset
### Context
A small subset of dataset of product reviews from Amazon Kindle Store category.

### Content
5-core dataset of product reviews from Amazon Kindle Store category from May 1996 - July 2014. Contains total of 982619 entries. Each reviewer has at least 5 reviews and each product has at least 5 reviews in this dataset.

### Columns
<ul>
  <li>asin - ID of the product, like B000FA64PK</li>
  <li>helpful - helpfulness rating of the review - example: 2/3.</li>
  <li>overall - rating of the product.</li>
  <li>reviewText - text of the review (heading).</li>
  <li>reviewTime - time of the review (raw).</li>
  <li>reviewerID - ID of the reviewer, like A3SPTOKDG7WBLN</li>
  <li>reviewerName - name of the reviewer.</li>
  <li>summary - summary of the review (description).</li>
  <li>unixReviewTime - unix timestamp.</li>
</ul>




### Which file to use?
The dataset originally contained a json file of the reviews, but some people had issues opening it and getting it to work so I've added a csv file which contains same data. You can use whichever one is easier to work with.

### Acknowledgements
This dataset is taken from Amazon product data, Julian McAuley, UCSD website. http://jmcauley.ucsd.edu/data/amazon/

License to the data files belong to them.

### Inspiration
<ul>
  <li>Sentiment analysis on reviews.</li>
  <li>Understanding how people rate usefulness of a review/ What factors influence helpfulness of a review.</li>
  <li>Fake reviews/ outliers.</li>
  <li>best rated product IDs, or similarity between products based on reviews alone (not the best idea ikr).</li>
  <li>Any other interesting analysis.</li>
  
</ul>




