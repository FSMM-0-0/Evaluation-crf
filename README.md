# Evaluation-crf
conlleval.pl evaluate of CRF test result (NER)    
The endOfChunk and start OfChunk should be changed when use.    
This code is matched BMOES labeling method.

# Format of Output
B-PER B-PER    
E-PER E-PER    
O O    
B-PER B-PER    
E-PER E-PER    
...    
    
the first tag is guessed and the second tag is correct.    
If the output is the standard format as follows, please comment the code from line 129 to line 131.  
    
Rockwell NNP B-NP B-NP    
International NNP I-NP I-NP    
Corp. NNP I-NP I-NP    
's POS B-NP B-NP    

the detailed description of it can be found in http://www.clips.uantwerpen.be/conll2000/chunking/output.html

# Use of script
``evaluation.pl < text``

# Environment Test
``perl -v``
