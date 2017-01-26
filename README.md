# text_utils

A place to put all short text-processing scripts that are used for Tibetan corpus analysis.

Working scripts:

...

In progress:

Pre-processing Tsheg-stripper: Takes any series of half-spaces, spaces, returns, line breaks, and line starts and normalizes them to a normal single space. Strips end tshegs and/or double tshegs. (The goal being a very standardized text where a single white space separates each and every Tibetan word).

To do:

File Pre-processing for Corpus Analysis - A script that takes a sub-set of corpus files (the 95 separate files that are all "Speech_Dialogs", for example) and dumps all their content into a single .txt file (Speech_Dialogs.txt in this case). Should be able to handle multiple input encodings and output should be in Unicode (a tool like WordSmith, for example, only likes Unicode). 
