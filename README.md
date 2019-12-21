# cky-parser

+ In this project we will implement the cky (cyk) algorithm for english that acts as recognizer as well as parser.

+ We will be using *NLTK* for representing cfg grammars and parse trees, but parser will be generated from scratch.

### Grammar :

The grammar stems from the Airline Travel Information System (ATIS), a project working on spoken dialog systems for air travel.
The *ATIS CFG* is available in the NLTK data package, together with 98 test sentences.


#### Language : Python

#### Modules : NLTK

##### Problem Statement :

  + Given a test sentence find whether the ATIS grammar covers the senetence or not ( Recognizer )
  + If the test sentence is derived from the grammar, print all the different parse trees of the sentence.
  + We will be using tree module in NLTK to draw the trees.
  
#### Running the program :

In the command prompt : python cky_parser.py

+ press   1 for parser and 2 for Recogniser

+ For parser : test sentence 89 in Test Sentences would run.
+ For recogniser : All the Atis sentences will be tested 


