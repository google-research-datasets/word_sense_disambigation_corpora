# word_sense_disambigation_corpora

##SemCor and Masc documents annotated with NOAD word senses.

This package includes SemCor and Masc documents annotated with NOAD (New Oxford American Dictionary) word senses.

The files are in XML format with DTD simple-wsd-doc.dtd.

We use the part-of-speech tags specified as follows:
-  .         		Punctuation
-  ADJ       	Adjectives
-  ADP       	Adpositions (prepositions and postpositions)
-  ADV       	Adverbs
-  CONJ      	Conjunctions
-  DET       	Determiners
-  NOUN      	Nouns (common and proper)
-  NUM       	Cardinal numbers
-  PRON      	Pronouns
-  PRT       	Particles or other function words
-  VERB      	Verbs (all tenses and modes)
-  X         	Other: foreign words, typos, abbreviations

The break level of a word indicates how it was separated from the previous token in the text:

-  NO_BREAK 		No separation between tokens.
-  SPACE_BREAK		Separated by space.
-  LINE_BREAK 		Separated by line break.
-  SENTENCE_BREAK	Separated by sentence break.

##Word sense mappings

This package also includes maps from NOAD word senses to WordNet senses.
1. manual_map.txt is a manually created map for a few word senses.
2. algorithmic_map.txt is built algorithmically.

Both files have the same format:
NOAD_word_sense\tWordNet_word_senses separated by comma

The above data is annoated with a crowdsourcing platform. The data is not guaranteed to be 100% accurate.

Please contact Dayu Yuan (dayuyuan@google.com) for classifications or further information.
