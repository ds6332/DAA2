# DAA2
ip_list.pkl is the pickle file for the sequence of input strings used to get the result and pat_list.pkl is the sequence of pattern strings used.
Number of strings in input=10000 and number of strings in pattern =100.
Run time and edit distance for each metric was calculated for 1 Million combinations of words randomly chosen from the dataset(https://github.com/dwyl/english-words/blob/master/words_alpha.txt). The words chosen vary in length from 3 characters to 10 characters.

Diagonal skipping method proposed by Kim(https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0251047) was implemented with k( value for mismatches) varying from 3 to 10.

Damerau Levenshtein distance was imported from the python package available at [fastDamerauLevenshtein](https://pypi.org/project/fastDamerauLevenshtein/)
