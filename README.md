# hawaiian-corpus - Data from a corpus of written Hawaiian

This repository contains data based on a corpus of texts written in the Hawaiian language (_ʻŌlelo Hawaiʻi_). The data includes frequency lists, stopwords, and lists of most common n-grams. The text in the corpus was obtained from [Ulukau](http://ulukau.org/), the Hawaiian Electronic Library.

There are a total of 10.7 million words in the corpus, which was restricted to modern (post-20th century) and non-scriptural text. An overview of statistics for the corpus (including the top most common words and n-grams) can be seen [here](corpus_stats-haw.md).

## Data

Files included in this repository:

* [Hawaiian frequency list](data/freqlist_haw.txt): A list of all the words in the corpus, arranged by frequency
* [Hawaiian stopwords list](data/stoplist_haw.txt): A list of stopwords derived from the frequency file (this is being actively verified and updated for eventual inclusion in the [stopwords-json](https://github.com/6/stopwords-json) project)
* [List of Hawaiian bigrams](data/ngrams/2grams_haw.txt) - A list of the most common sequences of two words, arranged by frequency
* [List of Hawaiian 3-grams](data/ngrams/3grams_haw.txt) - A list of the most common sequences of three words, arranged by frequency
* [List of Hawaiian 4-grams](data/ngrams/4grams_haw.txt) - A list of the most common sequences of four words, arranged by frequency
* [Statistics for the Hawaiian corpus](data/corpus_stats-haw.md)

## License

CC0.
