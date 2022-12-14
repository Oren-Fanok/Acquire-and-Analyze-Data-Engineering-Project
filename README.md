# Text-Mining-Acquire-and-Analyze-Project

# Overview

The jupyter notebook file contained in this submission functions to pull and store tweets from a variety of users and hashtags spanning conservative 
and liberal viewpoints in the United states. The acquisition of tweets and user information is done using elevated twitter API access.

Tweets are pulled from three handles and one hashtag for each of the two parties. Once tweets are pulled they are stored in dataframes according to political leaning. The pulled tweets are then cleaned and prepared for analysis.

There are four analyses performed within the jupyter notebook file. 

# Analysis 1: Most Popular Words and Organizations by Party

The first analysis determines the most popular words and groups by political party. These cells produce a bar chart visualization of the most popular words and another bar chart for most popular organizations. 

# Analysis 2: Text Patters by Party

The second analysis performed is an analysis of text patterns in each group of text (see my text patterns repository for specifics).

#Analysis 3: Spacy SVO Parsing by Party

Third, each group is run through a parsing analysis that outputs the 20 most common subject-verb-object (SVO) trios. 

# Analysis 4: Text Comparison between Parties

The text comparison analysis finds words disproportionately represented in each group when compared to the other political parties tweets. Please refer to my text comparison repo for more background.
