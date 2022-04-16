The table shows the comparison of modified/expanded version and original one.
Although the coverage of original ConceptNet is wider than the modified one, it contains numerous errors.
We refine the data, expand by different kinds of relations (mainly “Synonym”) and ensure the quality of ConceptNet.
Expanded ConceptNet is 3.21 times of the size of the original one.
In fact, the actual number of each statistic in original ConceptNet should be smaller, because numerous incorrect concepts are included.

In order to translate concept to machine-readable representation, word embedding is needed.
Average word embeddings of segmented words can’t fully represent or even differ from original meaning, especially when the concept contains ambiguous segmented words or the concept is a term that can’t be separated. Therefore, we decrease the number of multiple segmented ( > 1) concepts up to 44%, the words can be represented more precisely.

Take [賞 巴掌] (slap someone’s face) as an example (blank between two words means they are segmented).
“賞” means rewarding somebody for something, appreciating or admiring something.
“賞” in [賞 巴掌] means giving something to someone.
Word with ambiguities is hard to tell which one will be used in word embedding.
Paraphrase [賞 巴掌] to its similar concept [打耳光] to disambiguate.
