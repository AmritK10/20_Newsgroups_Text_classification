# 20_Newsgroups_Text_classification

## 20_Newsgroup Dataset
### Abstract
This data set consists of 20000 messages taken from 20 newsgroups.
### Sources
Original Owner and Donor<br/>
Tom Mitchell,<br/>
School of Computer Science,<br/>
Carnegie Mellon University
### Data Characteristics
One thousand Usenet articles were taken from each of the following 20 newsgroups.<br/>
    alt.atheism<br/>
    comp.graphics<br/>
    comp.os.ms-windows.misc<br/>
    comp.sys.ibm.pc.hardware<br/>
    comp.sys.mac.hardware<br/>
    comp.windows.x<br/>
    misc.forsale<br/>
    rec.autos<br/>
    rec.motorcycles<br/>
    rec.sport.baseball<br/>
    rec.sport.hockey<br/>
    sci.crypt<br/>
    sci.electronics<br/>
    sci.med<br/>
    sci.space<br/>
    soc.religion.christian<br/>
    talk.politics.guns<br/>
    talk.politics.mideast<br/>
    talk.politics.misc<br/>
    talk.religion.misc<br/>
Approximately 4% of the articles are crossposted. The articles are typical postings and thus have headers including subject lines, signature files, and quoted portions of other articles.
### Data Format
Each newsgroup is stored in a subdirectory, with each article stored as a separate file.
### Link to the Dataset
http://archive.ics.uci.edu/ml/datasets/Twenty+Newsgroups
## Implementation
Multinomial Naive Bayes was used to classify a given article into one of the 20 newsgroups.The Multinomial Naive Bayes implementation from sklearn aswell as my own self implementation were used for the classification and their results were compared.It was seen that both the implementations gave the exact same results hence both the implementations must be same.
## Accuracy
### Sklearn's implementation
Testing accuracy : 82.16%<br/>
F1 score: 0.82
### Self implementation
F1 score: 0.82
