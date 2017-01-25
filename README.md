# contextual-suggestion
These files contain the datas and codes for the contextual suggestion based on the users previous ratings.

The requests.text file has the users rating provided to us so that we can use that information to provide the contextual suggestion, we can see that we have rating corresponding to every word and document id(URL from where hte word has been extracted)

The list of annotations.txt file has code for converting plural to singular and selecting relevant words.

The url_dictionary.txt file has URL list corresponding to every Document Id.

The final_tags_list.txt has a manually prepared and indexed list of words, if the word is indexed as "0" , it has to be matched "one by one" if indexed as "1" it has to be matched with the given word list, if indexed as "2", we need to explore the words by using 'wordnet' and then it needs to be matched.

The the_original_program.txt has the main code.

The result2.txt has the input document Id's and also the output arranged document Id's according to previous datas.
