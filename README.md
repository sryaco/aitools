Readme.md

 Aitools repository
 AI tools tested on the William Elliot Griffis manuscript collection at Rutgers University Libraries

Sonia Yaco
Rutgers University
2024

Locations:
Notebooks are in \notebooks
Photographs
A small number of photos that can be used for clustering and mapping are in \data and \data\photos

The full corpus of digitized Griffis Japan images used in testing, 427 tiff files, 10 Gig is available for download from: Google Drive -https://drive.google.com/drive/folders/1U-NIDpXC5cUOzNW0fZ0H8mk9Q5PH3xgG?usp=drive_link   

Program names with descriptions 
Cosine_similarity.ipynb
Compares two utf-8 formatted texts and calculates the cosine similarity.

Image_cluster.ipynb
Creates 4 groups of photos, groups by content similarly. Prints 5 of each group.

Image_clustermatch.ipynb
•	Image clustering
Creates 4 groups of photos, groups by content similarly. Prints 7 of each group on screen and to png file 
•	Matches one images to all, selecting 5 closest. No reprocessing of corpus is needed so it can be re-run quickly, changing file names each time of a photo to match. Original picture is displayed, then 5 matches.

Image_match.ipynb
Provides the top 5 most similar images to one  selected image, based on VVG16 pattern similarity.

NER.ipynb
Three routines:
•	NER alpha order by word
Spacy and NLTK create ner lists in output file, in word order

•	 NER in category order
Spacy and NLTK create ner lists in output file, sorted by NER category

•	 NER color coded word visualizations – two versions
o	All NERs are shown color coded in context
o	Just three filtered labels, ('PERSON', 'ORG', 'GPE') are shown in original word order but no context.

ngrams.ipynb
Builds three lists of n-grams from first input file (diary), second input file (biography), and common to both. Defaults to n-grams length of 1.

Sentiment_analysis.ipynb
Produces numeric scores and visual graph of sentiment by paragraph. Output to screen and text and png file.

