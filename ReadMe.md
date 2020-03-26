install requirement
---
pip install -r requirements.txt
-----

download stanford nlp from
http://nlp.stanford.edu/software/stanford-corenlp-full-2018-10-05.zip

unzip download package. (linux command)
unzip stanford-corenlp-full-2018-10-05.zip

move to folder :
cd stanford-corenlp-full-2018-10-05

Start the CoreNLP server:
java -mx4g -cp "*" edu.stanford.nlp.pipeline.StanfordCoreNLPServer -port 9000 -timeout 15000

open file with jupyter notebook
run

thank you