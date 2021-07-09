# die_vs_dat
Probing for relative pronouns in Dutch relative clauses

Data used in the probing experiments and jupyter notebook for probing the language models. 

Data are from the CLEF corpus (used previously in several CLEF question answering evaluation campaigns). 

clef.np1/np2.* are high and low attachment cases respectively.

clef.*.rmask files are identical to mask except that the mask is written as <mask> instead of [MASK].
  
The *.rc.mask files are synthetic data used for regression testing, where left and right contexts where left contexts have been combined with a random right context with either a matching or nonmatching rel pronoun. 
  
  
