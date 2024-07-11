# Surprisal and RTs Final project in Language Computation and Cognition course

In our project we will be working on surprisal and
reading time, examining the relation between reading times
and surprisal using different models and techniques. We will
analyze the performance of RNN model, NGRAM model,
and performance of neural networks models on different datasets. 

Our main task will examine the effect of texts from different time periods on the model’s ability to predict surprisal
on modern text and it’s relation to it’s reading time.

Surprisal refers to the level of unexpectedness or unpredictability of a word or phrase within a given context. It plays
a crucial role in measuring human reading comprehension
and cognitive load. Reading time, on the other hand, reflects
the duration required for an individual to process and comprehend a given text segment. 

Through out our tasks we will
be examining the Smith and Levy (2013) self-paced reading
data-set derives from each subject in the experiment reading a
number of several-hundred-word passages selected from the
Brown corpus (Kucera and Francis, 1967).

We also trained models on books from different eras and examining the influences it has on their predictive abilities, specifically in terms of surprisal and reading time. By training our
language model on books from different historical periods,
we aim to investigate how exposure to varied linguistic styles,
vocabularies, and cultural contexts affects the model’s ability to predict surprisal and estimate reading time accurately.

**Summary**

In our work we explored the abilities of different models to
predict the surprisals of words and view its correlation to real
reading time measured from experiments. We viewed two
main models, RNN and N-Gram with N = 5. Over all we received that the RNN model was better at computing and predicting the surprisal that matches the reading time. As RNN
are known for being able to capture the whole context of the
sentence which is very important for predicting the surprisal
of the word, unlike the N-Gram model which was only exposed to the previous 5 words.

We hoped to view that the
size of the data the models were trained on would improve
the relation between surprisal and reading time for both models, but when training the models on Wikitext-2 we did not
receive better results. This led us to the understanding that
it is not only the size of the dataset that matters but it’s context as well. Wikitext-2 is more of a theoretical and scientific dataset, based on Wikipedia pages whose purpose are to
teach and transfer knowledge, which is different that the style
of our test data, Brown corpus, from which the reading time
was extracted, which consists of a diverse range of texts from
various genres, including fiction, non-fiction, news articles,
and conversations.

We also explored the way texts from different eras are able
to predict surprisal to match reading time, by training RNN
models of books from different eras. The model trained on
modern book received the best correlation to the reading time.
The Brown Corpus was created in 1967, so it may not capture
more recent linguistic phenomena or changes in the English
language. We hoped to
view that the book written closest to the time of Brown would
receive better correlation to reading time though it ended up
achieving the worst correlation. One explanation is the size of
the book, which is significantly smaller than the other books
tested. Also, we saw in the cross comparison that out two
most modern books performed well on each other, so probably the evolving of the literature language wasn’t too dramatic
in the time that pasted between the publication of these books.

In general, in all of our models and experiments we did not
view a strong correlation between the predicted surprsial and
the reading time. Further research and exploration around
these relations is needed. Evaluating more elements that effect the reading time, usage of part-of-speech tags and syntactic tree structures or multi modal data such as eye movements
to improve measuring reading time. Also experimenting the
use of more advance models, LLM’s, that are better on capturing the full context of the text which has a high effect on
the surprisal and reading time.
