# Sentiment Analysis on Movie Reviews with Keras LSTM

## Data Description
The dataset is comprised of tab-separated files with phrases from the Rotten Tomatoes dataset. The train/test split has been preserved for the purposes of benchmarking, but the sentences have been shuffled from their original order. Each Sentence has been parsed into many phrases by the Stanford parser. Each phrase has a PhraseId. Each sentence has a SentenceId. Phrases that are repeated (such as short/common words) are only included once in the data.

train.tsv contains the phrases and their associated sentiment labels. We have additionally provided a SentenceId so that you can track which phrases belong to a single sentence.
test.tsv contains just phrases. You must assign a sentiment label to each phrase.

<b> The sentiment labels are : <b>

<table>
<tr>
<td>0 - negative</td>
<td>1 - somewhat negative</td>
<td>2 - neutral</td>
<td>3 - somewhat positive</td>
  <td>4 - positive</td>
  </tr>
