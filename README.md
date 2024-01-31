# aitools
AI tools tested on the WIlliam Elliot Griffis manuscript collection at Rutgers University Libraries

Paths to notebooks and data will need to be modified
Test image data, 427 tiff files,  is available for download from: Google Drive ----------------------


**Task	Program name 	Description 
NER	NER.ipynb	NER alpha order by word
Spacy and NLTK create ner lists in output file, in word order
		# NER in category order
Spacy and NLTK create ner lists in output file, sorted by NER category
		# NER color coded word visualizations
First 
all NERs are shown color coded in context
then just three filtered labels, ('PERSON', 'ORG', 'GPE'
) are shown in original word order but no context.
N-Grams	ngrams.ipynb	#Builds three lists of n-grams from first input file (diary), second input file (biography), and common to both. Defaults to n-grams length of 1

Similarity cosine	cosine_similarity.ipynb	Compare two utf-8
formatted texts and calculates the cosine similarity
Sentiment analysis	Sentiment_analysis	Produces numeric scores and visual graph of sentiment by paragraph. Output to screen and text and png file.
Photo clustering
	Image_clustering	Creates 4 groups of photos, groups by content similarly. Prints 5 of each group

Photo matching	Matchphotos	Provides the top 5 most similar images to one  selected image, based on VVG16 pattern similarity
Photo matching	Image_clustermatch	#image clustering
#Creates 4 groups of photos, groups by content similarly. Prints 7 of each group on screen and to png file 
#Then matches one images to all, selecting 5 closest. No reprocessing of corpus 
# is needed so can be re-run quickly, changing file name of photos to match.
#orginal picture is displayed, then 5 matches.
#currently doesn't print matches to file
**
