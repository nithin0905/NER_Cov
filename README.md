# NER_Cov
In this project we have tried to extract information that seeks to locate and classify named entities mentioned in unstructured text into pre-defined categories such as he terms related to Covid. We have tried creating our own word list/dictionary and implemented multiple preprocessing techniques to clean the text such as stemming, lemmatization, removal of stopwords etc.,

NER USING CRF

The goal of a named entity recognition (NER) system is to identify all textual mentions of the named entities. This can be broken down into two sub-tasks: identifying the boundaries of the NE, and identifying its type.

Named entity recognition is a task that is well-suited to the type of classifier-based approach. In particular, a tagger can be built that labels each word in a sentence using the IOB format, where chunks are labelled by their appropriate type.

The IOB Tagging system contains tags of the form:

B - {CHUNK_TYPE} – for the word in the Beginning chunk
I - {CHUNK_TYPE} – for words Inside the chunk
O – Outside any chunk
