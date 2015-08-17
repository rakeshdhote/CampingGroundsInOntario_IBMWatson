# Using IBM Watson for Mining Information of Camping Grounds in Ontario

The repo consists of the final project and presentation of using the cognitive computing and natural language processing (NLP) platform the `IBM Watson` for mining the relevant information to the queries regarding the camping grounds in Ontario, Canada. The team project was prepared as a part of the `CKME-130: Introduction to the Data Science` course in the `Data Analytics, Big Data, and Predictive Analytics` certification program at the [Ryerson University](www.ryerson.ca). 

There are more than 125 government operated parks(or grounds) in the Ontario. Searching  for  relevant  information  on  park  and  tourism websites  can  be  overwhelming  and  time consuming. The objective of this project is to provide a way for obtaining information related to camping in  Ontario  parks  in  a  simpler,  time  efficient  manner  relative  to  a  traditional  website  search.

We leveraged the power of a cognitive computing platform, the `IBM Watson`, to mine information based on questions  expressed  in  NLP.   Information  about  camping  was  collected  from  the  Ontario Parks website and uploaded onto Watson's corpus. A web-scraping Python script was created to parse the HTML files of each of the parks listed on the website. A  total  of  340  question-answer (QA)  pairs  were generated to train the Watson QA system. Out of the 25 questions asked in the test phase, the current QA system could generate 67\% relevant answers. The performance of the current QA system might be improved by training it with more QA pairs or including information from other resources.

A Python web scraping script is developed to extract 126 parks information from the [OntarioParks.com](OntarioParks.com) website. The script writes parks information in the `Microsoft Word` formatted document. This document serves an input to train the `IBM Watson` for predicting the appropriate park based on the asked question.

The script uses the following Python packages:
*  BeautifulSoup  
*  Requests  
*  docx.

The project is for educational purpose and not intended to use for any commercial applications. 



