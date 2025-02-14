Taylor Swift is one of the world’s most well-known and successful musical arƟsts. This project explores the musical style of Swift’s albums by
employing machine learning techniques in an attempt to identify whether an album can be predicted using the audio attributes of its songs.
The dataset used here was originally collected using the Spotify API. For each song, it lists various audio attributes, such as danceability or
energy, as well as the album name. As such, this study aims to quantify how distinctive the musical style of each album is, as well as to
compare which machine learning classificaƟon algorithm performs best on this dataset.

To answer these quesƟons, four supervised learning algorithms were applied to the data. These were k-Nearest Neighbor, Gaussian NaïveBayes, Decision Tree and Random Forest. The performance of each algorithm was evaluated using precision and recall, in addiƟon to
accuracy. Moreover, techniques such as nested cross-validaƟon and the scikit-learn GridSearchCV feature were used to tune the models’
hyperparameters and to reduce the risk of overfitting.

The results show that the weighted k-Nearest Neighbor algorithm performed best on this dataset, achieving an accuracy score of
approximately 0.6, as well as recall and precision scores of over 0.7 for certain albums. Furthermore, the results for each algorithm showed
that the recall and precision scores for some albums were consistently much higher than for others. For instance, the albums ‘1989’,
‘Midnights’, ‘Red’, ‘Speak Now’, ‘evermore’ and ‘folklore’ were classified correctly to a much greater extent than ‘reputaƟon’ or ‘Lover’,
which received recall scores of 0.2 and 0.13 using k-NN. Moreover, the algorithms frequently misclassified songs belonging to ‘evermore’ as
belonging to ‘folklore’ and vice versa, indicating that these albums are similar in style. These scores suggest that some albums might have a
more disƟncƟve musical style than others, as well as confirming popular opinions that SwiŌ dramaƟcally changed her style during the
COVID-19 pandemic when she released ‘folklore’, closely followed by ‘evermore’.

Consequently, this project demonstrates how machine learning can be used to trace the evoluƟon of a singer’s musical evolution over the
span of their career, as well as explaining why certain albums might have been more successful than others due to shifts in their audio
attributes. Some suggestions for future improvements include applying k-Means Clustering to reveal more patterns and structures within
the song’s audio characterisƟcs. Finally, the project evaluaƟon provides a discussion of how more advanced techniques for dealing with
imbalanced datasets, such as this one, could be applied to further refine these models. 
