# may2026_dblp

Downloaded data file of DBLP from this link: https://dblp.uni-trier.de/xml/

Go to this link above and download the dblp.xml.gz file, which decompresses into a dblp.xml file.

I cloned this repository, which turned into the dblp-parser directory. https://github.com/angelosalatino/dblp-parser 

Put dblp.xml in the dblp-parser directory, and run the dblp-parser/test.py script, which writes the dblp-parser/dblp.jsonl file. 

Finally, run the dblp_parse.ipynb file in the outermost directory, which writes to the new_dblp_query.csv file. This is the output that we want.
