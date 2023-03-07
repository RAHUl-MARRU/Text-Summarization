# Text-Summarization
NATURAL LANGUAGE PROCESSING

# Problem Definition

In this project I doing that in general, if any person wants to know about any information, they
need to read the entire text. But this is not possible in all cases. We cannot get an idea just by
reading a part of it. There may be different meanings in another part. So, to get a clear
understanding we need to read every line of the text. In the present day, people are leading very
busy lives and lack patience in reading such tedious texts. Taking all the factors into
consideration such as less time, precise text and patience we need to reduce the length of the text
without lacking in exact meaning. The main aim of the project is to summarize the text base on
all the factors. Through the proposed method of ours, summarization of the text can be easily
done and can help people to know everything in particular of what they are about to do. This can
avoid people to misuse their information unknowingly.

# Approach

In this project I am using Extractive Text Summarization , which will extract the important
sentences and gives the abstract for the document that helps in understanding easily. Text
Summarization is implemented using an unsupervised Text Rank Algorithm. Graphical User
Interfaces are created using advanced NLTK techniques. The input can be in the form of large
chunks of text and any text document which is stored in your local hard disk.
Mainly focusing on unsupervised machine learning is used on the text given by the user. First we
need to collect the document which contains text. The text can be in a file or any text document
which is stored in your local hard disk or any URL.

# Implementation

![image](https://user-images.githubusercontent.com/125625532/223333982-63a5ba1c-abcd-4a70-8ad9-18bf4ba5edde.png)

# Modules Used

NLTK, Corpus, Tokenizer, TKINTER, Window, TopLevelWindow, Frame, Widget, and TTk.

# Following steps by using unsupervised technique:


1. Gather data

2. Perform Pre-Processing

    a. Delimiter removal - (, . ‘ “ ? ! )
    
    b. Stop word removal (which are mostly used by user) - the, is, an, a, like etc.
    
    c. Stem word Removal (adjective or adverb of a word) - (ied, ed, mis, ary)
    
3. Weighted word frequency

4. calculating vectors for every sentence

5. Sentences scores by using text rank algorithm

6. Adding the highest sentence scores to summary

# Conclusion

The purpose of summarization of text is to interpret the source text as a condensed edition with
the words preserved, to express the contents of a document in a succinct way in order to satisfy
customers’ needs. The main aim of this project is to collect the important keywords from the
provided agreements or the manuals and give the user a brief and short summary for the input.


# Future Scope:


Future work aims at improving the extraction on important keywords, a framing the sentences
based on the extracted keywords. This is called abstractive summarization. we’ll discuss the
descriptive methodology of overview text where profound thinking plays a major part.
Summarization can also be worked on with the help of machine learning, deep learning
techniques.Two reasonable recommendations may be to change the topic-oriented outline
framework for news and blogs and extend the analysis machine-leaning methods. Summaries of
the news reports are often more descriptive and accessible to users. Research on subject
modeling and resuming in the area of social networking would be more relevant in the future.
