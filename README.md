<!--- [![HitCount](http://hits.dwyl.io/binny-mathew/Hate-Speech-Reading-List.svg)](http://hits.dwyl.io/binny-mathew/Hate-Speech-Reading-List) --->
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fbinny-mathew%2FHate-Speech-Reading-List)](https://hits.seeyoufarm.com)
<!--- [![forthebadge](https://forthebadge.com/images/badges/powered-by-responsibility.svg)](https://forthebadge.com) --->

# Reading List for Hate Speech Research 📖
A reading list of relevant research papers on Hate speech and related issues. This list is maintained by [Binny Mathew](https://binny-mathew.github.io) and [Punyajoy Saha](https://punyajoy.github.io), at [CNeRG Lab](http://www.cnergres.iitkgp.ac.in/), [IIT Kharagpur](http://www.iitkgp.ac.in)

  In the past few years we have witnessed an increase in the number of hate speech incidents world wide. While there is a rich literature in the social sciences, the research on the computational aspects have just started. This list is an effort to create a *one stop comprehensive* guide for all research related to Hate Speech. The list is still incomplete and the categorization might be inappropriate. 
 
 We will keep adding papers and improving the list. Any suggestions are super welcome :smile:
 

## <a name='TOC'>Table of Contents</a>

  1. [Introduction](#intro)
  2. [Dataset Papers](#datasets)
  3. [Survey Papers](#survey)
  4. [Interesting Papers](#top10)
  5. [Code Available](#code)
  6. [Shared Tasks](#sharedtasks)
  7. [Papers](#langwise)
      - [Amharic](#langAmharic)
      - [Arabic](#langAra)
      - [Dutch](#langDutch)
      - [English](#langEng)
      - [German](#langGer)
      - [Hindi](#langHin)
      - [Indonesian](#langIndo)
      - [Italian](#langItalian)
      - [Kenya](#langKenya)
  8. [Videos](#video)
  9. [Blogs](#blog)
  10. [Interesting Reads](#interReads)
  
  


## <a name='intro'> Introduction
  
The Internet is one of the greatest innovations of mankind which has brought together people from every race, religion, and nationality. Social media sites such as Twitter and Facebook have connected billions of people and allowed them to share their ideas and opinions instantly. That being said, there are several ill consequences as well such as online harassment, trolling, cyber-bullying, and **hate speech**.
  



## <a name='datasets'> Datasets
  * Yi-Ling Chung, Elizaveta Kuzmenko, Serra Sinem Tekiroglu, and Marco Guerini. [CONAN - COunter NArratives through Nichesourcing:a Multilingual Dataset of Responses to Fight Online Hate Speech](https://www.aclweb.org/anthology/P19-1271.pdf). 2019. *ACL*
  * Jing Qian, Anna Bethke, Yinyin Liu, Elizabeth Belding, and William Yang Wang. [A Benchmark Dataset for Learning to Intervene in Online Hate Speech"](https://arxiv.org/abs/1909.04251). 2019. *arXiv*
  * Jing Qian, Mai ElSherief, Elizabeth Belding, and William Yang Wang. [Learning to Decipher Hate Symbols](https://arxiv.org/abs/1904.02418). 2019. *NAACL*
  * Binny Mathew, Hardik Tharad, Subham Rajgaria, Prajwal Singhania, Suman Kalyan Maity, Pawan Goyal, and Animesh Mukherje. [Thou shalt not hate: Countering Online Hate Speech](https://arxiv.org/abs/1808.04409). 2019. *ICWSM*
  * Antigoni-Maria Founta, Constantinos Djouvas, Despoina Chatzakou, Ilias Leontiadis, Jeremy Blackburn, Gianluca Stringhini, Athena Vakali, Michael Sirivianos, and Nicolas Kourtellis. [Large Scale Crowdsourcing and Characterization of Twitter Abusive Behavior](https://arxiv.org/abs/1802.00393). 2018. *ICWSM*
  * Ziqi Zhang, David Robinson, and Jonathan Tepper. [Detecting hate speech on Twitter using a convolution-GRU based deep neural network](https://link.springer.com/chapter/10.1007/978-3-319-93417-4_48). 2018.  *European Semantic Web Conference*
  * Ona de Gibert, Naiara Perez, Aitor García Pablos, and Montse Cuadros. [Hate Speech Dataset from a White Supremacy Forum](http://www.aclweb.org/anthology/W18-51#page=25). 2018. *ALW2*
  * Manuela Sanguinetti, Fabio Poletto, Cristina Bosco, Viviana Patti, and Stranisci Marco. [An italian Twitter corpus of hate speech against immigrants](https://iris.unito.it/bitstream/2318/1686261/1/710.pdf). 2018. *LREC ELRA*
  * Mai ElSherief, Vivek Kulkarni, Dana Nguyen, William Yang Wang, and Elizabeth Belding. [Hate lingo: A target-based linguistic analysis of hate speech in social media](https://www.aaai.org/ocs/index.php/ICWSM/ICWSM18/paper/viewPaper/17910). 2018. *ICWSM*
  * [GAB Dataset Link](https://zenodo.org/record/1418347) --> [What is gab: A bastion of free speech or an alt-right echo chamber](https://dl.acm.org/citation.cfm?id=3191531). 2018 . *WWW*
  * Thomas Davidson, Dana Warmsley, Michael Macy, and Ingmar Weber. [Automated hate speech detection and the problem of offensive language](https://arxiv.org/pdf/1703.04009.pdf). 2017. *ICWSM*
  * Lei Gao, and Ruihong Huang. [Detecting Online Hate Speech Using Context Aware Models](http://www.acl-bg.org/proceedings/2017/RANLP%202017/pdf/RANLP036.pdf). 2017. *RANLP*
  * Zeerak Waseem and Dirk Hovy. [Hateful symbols or hateful people? predictive features for hate speech detection on twitter](http://www.aclweb.org/anthology/N16-2013). 2016. *NAACL SRW*
  * [Dataset Link](https://github.com/Mainack/hatespeech-data-HT-2017) for the paper [A Measurement Study of Hate Speech in Social Media](https://dl.acm.org/citation.cfm?id=3078723)
  * [Dataset Link](https://github.com/UCSM-DUE/IWG_hatespeech_public) for the paper [Measuring the Reliability of Hate Speech Annotations:The Case of the European Refugee Crisis](https://arxiv.org/pdf/1701.08118.pdf).


## <a name='survey'> Survey Papers
  
  * Paula Fortuna and Sérgio Nunes. [A survey on automatic detection of hate speech in text](https://dl.acm.org/citation.cfm?id=3232676). 2018. *ACM Computing Surveys (CSUR)*
  * Anna Schmidt and Michael Wiegand. [A survey on hate speech detection using natural language processing](http://www.aclweb.org/anthology/W17-1101). 2017. *SocialNLP*
  
  
  

## <a name='top10'> Interesting Papers
  
  
  * Aymé Arango, Jorge Pérez and Barbara Poblete,[Hate Speech Detection is Not as Easy as You May Think: A Closer Look at Model Validation](https://users.dcc.uchile.cl/~jperez/papers/sigir2019.pdf). 2019 . [*SIGIR*](http://www.sigir.org/sigir2019/program/accepted/)
  * Iginio Gagliardone, Danit Gal, Thiago Alves, and Gabriela Martinez. [Countering online hate speech](https://books.google.co.in/books?hl=en&lr=&id=WAVgCgAAQBAJ&oi=fnd&pg=PA3&dq=hate+speech&ots=Tb6s3jFMUz&sig=w16Mus9ctU7sE-utDFYUGAgf3EU#v=onepage&q=hate%20speech&f=false). 2015. *Unesco Publishing*
  
  
## <a name='code'> Code Available
  
  * [Automated Hate Speech Detection and the Problem of Offensive Language](https://github.com/t-davidson/hate-speech-and-offensive-language)
  * [Deep Learning for Hate Speech Detection in Tweets](https://github.com/pinkeshbadjatiya/twitter-hatespeech)
  * [Hateminers: Detecting Hate speech against Women](https://github.com/punyajoy/Hateminers-EVALITA)
  * [Detecting Online Hate Speech Using Context Aware Models](https://github.com/sjtuprog/fox-news-comments)
  * [CLiPS HAte speech DEtection System (HADES)](https://github.com/clips/hades)
  
  
  
  
  
## <a name='sharedtasks'> Shared Tasks
  
  * Cristina Bosco, Dell'Orletta Felice, Fabio Poletto, Manuela Sanguinetti, and Tesconi Maurizio. [Overview of the EVALITA 2018 Hate Speech Detection Task](http://ceur-ws.org/Vol-2263/paper010.pdf). 2018. *EVALITA*
  * Valerio Basile, Cristina Bosco,Elisabetta Fersini,Debora Nozza, Viviana Patti, Francisco Rangel ,Paolo Rosso and Manuela Sanguinetti, Page 54-63, [Proceedings of 13th SemEval Workshop](http://alt.qcri.org/semeval2019/data/uploads/semeval2019-proceedings.pdf). Archived competition link-[HatEval@SemEval 2019](https://competitions.codalab.org/competitions/19935)
  * Valerio Basile, Cristina Bosco, Elisabetta Fersini, Debora Nozza, Viviana Patti, Francisco Manuel Rangel Pardo, Paolo Rosso, and Manuela Sanguinetti. [Semeval-2019 task 5: Multilingual detection of hate speech against immigrants and women in twitter](https://www.aclweb.org/anthology/S19-2007/). 2019. *International Workshop on Semantic Evaluation*
  
## <a name='langwise'> Language Wise
  
  
  
  
  ### <a name='langAmharic'> Amharic
  
  #### 2018
  
  * Zewdie Mossie, and Jenq-Haur Wang. [SOCIAL NETWORK HATE SPEECH DETECTION FOR AMHARIC LANGUAGE](http://aircconline.com/csit/csit886.pdf#page=51). 2018. *Computer Science & Information Technology*
  
  
  
  

### <a name='langAra'> Arabic
  #### 2019
  
  * Arijit Ghosh Chowdhury, Aniket Didolkar, Ramit Sawhney and Rajiv Ratn Shah. [ARHNet - Leveraging Community Interaction For Detection Of ReligiousHate Speech In Arabic](https://www.aclweb.org/anthology/P19-2038.pdf). 2019. *ACL:Student Research Workshop*
  
  #### 2018
  
  * Nuha Albadi, Maram Kurdi, and Shivakant Mishra. [Are they Our Brothers? Analysis and Detection of Religious Hate Speech in the Arabic Twittersphere](https://ieeexplore.ieee.org/abstract/document/8508247). 2018. *ASONAM*
  * Sarah Eissa. [Use of hate speech in Arabic language newspapers](http://dar.aucegypt.edu/handle/10526/5249) (2018).





### <a name='langDutch'> Dutch
  
  #### 2016
  
  * Stéphan Tulkens, Lisa Hilte, Elise Lodewyckx, Ben Verhoeven, and Walter Daelemans. [A Dictionary-based Approach to Racism Detection in Dutch Social Media](https://www.ta-cos.org/sites/ta-cos.org/files/dictionary-based-approach.pdf). 2016. *TA-COS*
  
  
 
 
 

### <a name='langEng'> English
  
  #### 2019
  * Pinkesh Badjatiya, Manish Gupta, and Vasudeva Varma. [Stereotypical bias removal for hate speech detection task using knowledge-based generalizations](https://arxiv.org/pdf/2001.05495.pdf). 2019. *The World Wide Web Conference (WWW)*
  * Maarten Sap, Dallas Card, Saadia Gabriel, Yejin Choi, Noah A. Smith. [The Risk of Racial Bias in Hate Speech Detection](https://www.aclweb.org/anthology/P19-1163.pdf). 2019. *ACL*
  * Thomas Davidson, Debasmita Bhattacharya, and Ingmar Weber. [Racial Bias in Hate Speech and Abusive Language Detection Datasets](https://arxiv.org/abs/1905.12516). 2019. *arXiv*
  * Wafa Alorainy, Pete Burnap, Han Liu, and Matthew L. Williams. ["The Enemy Among Us": Detecting Cyber Hate Speech with Threats-based Othering Language Embeddings](https://dl.acm.org/citation.cfm?id=3324997). 2019. *ACM Transactions on the Web (TWEB)*
  * Jing Qian, Anna Bethke, Yinyin Liu, Elizabeth Belding, and William Yang Wang. [A Benchmark Dataset for Learning to Intervene in Online Hate Speech"](https://arxiv.org/abs/1909.04251). 2019. *arXiv*
  * Kristian Miok, Dong Nguyen-Doan, Blaž Škrlj, Daniela Zaharie, and Marko Robnik-Šikonja. [Prediction Uncertainty Estimation for Hate Speech Classification](https://arxiv.org/abs/1909.07158). 2019. *arXiv*
  * Jing Qian, Mai ElSherief, Elizabeth Belding, and William Yang Wang. [Learning to Decipher Hate Symbols](https://arxiv.org/abs/1904.02418). 2019. *arXiv*
  * Binny Mathew, Punyajoy Saha, Hardik Tharad, Subham Rajgaria, Prajwal Singhania, Suman Kalyan Maity, Pawan Goyal, and Animesh Mukherje. [Thou shalt not hate: Countering Online Hate Speech](https://arxiv.org/abs/1808.04409). 2019. *ICWSM*
  * Binny Mathew, Ritam Dutt, Pawan Goyal, and Animesh Mukherjee. [Spread of hate speech in online social media](https://arxiv.org/abs/1812.01693). 2019. *WebSci*
  * Pushkar Mishra, Marco Del Tredici, Helen Yannakoudakis, and Ekaterina Shutova. [Author Profiling for Hate Speech Detection](https://arxiv.org/abs/1902.06734). 2019. *arXiv*
  * T. Y. S. S. Santosh, and K. V. S. Aravind. [Hate Speech Detection in Hindi-English Code-Mixed Social Media Text](https://dl.acm.org/citation.cfm?id=3297048). 2019. *CoDS-COMAD*
  * Junanda Patihullah, and Edi Winarko. [Hate Speech Detection for Indonesia Tweets Using Word Embedding And Gated Recurrent Unit](https://journal.ugm.ac.id/ijccs/article/view/40125). 2019. *IJCCS*
  
  #### 2018
  
  * Wiktor Soral, Michał Bilewicz, and Mikołaj Winiewski. [Exposure to hate speech increases prejudice through desensitization](https://onlinelibrary.wiley.com/doi/abs/10.1002/ab.21737). 2018. *Aggressive behavior*
  * Mai ElSherief, Shirin Nilizadeh, Dana Nguyen, Giovanni Vigna, and Elizabeth Belding. [Peer to peer hate: Hate speech instigators and their targets](https://www.aaai.org/ocs/index.php/ICWSM/ICWSM18/paper/viewPaper/17905). 2018. *ICWSM*
  * Savvas Zannettou, Barry Bradlyn, Emiliano De Cristofaro, Haewoon Kwak, Michael Sirivianos, Gianluca Stringini, and Jeremy Blackburn. [What is gab: A bastion of free speech or an alt-right echo chamber](https://dl.acm.org/citation.cfm?id=3191531). 2018. *WWW*
  * Punyajoy Saha, Binny Mathew, Pawan Goyal, and Animesh Mukherjee. [Hateminers: Detecting Hate speech against Women](https://arxiv.org/abs/1812.06700). 2018. *arXiv*
  * Resham Ahluwalia, Himani Soni, Edward Callow, Anderson Nascimento, and Martine De Cock. [Detecting Hate Speech Against Women in English Tweets](http://ceur-ws.org/Vol-2263/paper032.pdf). 2018. *EVALITA*
  * Ziqi Zhang, and Lei Luo. [Hate speech detection: A solved problem? The challenging case of long tail on Twitter](https://content.iospress.com/articles/semantic-web/sw180338). 2018. *Semantic Web Preprint*
  * Karsten Müller, and Carlo Schwarz. [Fanning the flames of hate: Social media and hate crime](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3082972). 2018. *SSRN*
  * Jing Qian, Mai ElSherief, Elizabeth Belding, and William Yang Wang. [Leveraging Intra-User and Inter-User Representation Learning for Automated Hate Speech Detection](http://www.aclweb.org/anthology/N18-2019). 2018. *NAACL*
  * David Robinson, Ziqi Zhang, and Jonathan Tepper. [Hate speech detection on twitter: Feature engineering vs feature selection](https://link.springer.com/chapter/10.1007/978-3-319-98192-5_9). 2018. *European Semantic Web Conference*
  * Jing Qian, Mai ElSherief, Elizabeth Belding, and William Yang Wang. [Hierarchical CVAE for Fine-Grained Hate Speech Classification](http://www.aclweb.org/anthology/D18-1391). 2018. *EMNLP*
  * Tommi Gröndahl, Luca Pajola, Mika Juuti, Mauro Conti, and N. Asokan. [All You Need is "Love": Evading Hate-speech Detection](https://arxiv.org/abs/1808.09115). 2018. *arXiv*
  * Shervin Malmasi, and Marcos Zampieri. [Challenges in discriminating profanity from hate speech](https://www.tandfonline.com/doi/abs/10.1080/0952813X.2017.1409284). 2018. *Journal of Experimental & Theoretical Artificial Intelligence*
  * Joel Finkelstein, Savvas Zannettou, Barry Bradlyn, and Jeremy Blackburn. [A quantitative approach to understanding online antisemitism](https://arxiv.org/abs/1809.01644). 2018. *arXiv*
  * Alexandra Olteanu, Carlos Castillo, Jeremy Boy and Kush R. Varshney. [The Effect of Extremist Violence on Hateful Speech Online](https://arxiv.org/pdf/1804.05704.pdf). 2018. *ICWSM*
  * Bertie Vidgen, and Taha Yasseri. [Detecting weak and strong Islamophobic hate speech on social media](https://arxiv.org/abs/1812.10400). 2018. *arXiv*
  * Manoel Horta Ribeiro, Pedro H. Calais, Yuri A. Santos, Virgílio AF Almeida, and Wagner Meira Jr. [Characterizing and detecting hateful users on twitter](https://www.aaai.org/ocs/index.php/ICWSM/ICWSM18/paper/viewPaper/17837). 2018. *ICWSM*
  * Joni Salminen, Fabio Veronesi, Hind Almerekhi, Soon-Gvo Jung, and Bernard J. Jansen. [Online Hate Interpretation Varies by Country, But More by Individual: A Statistical Analysis Using Crowdsourced Ratings](https://ieeexplore.ieee.org/abstract/document/8554954/). 2018. *SNAMS*
  * Phoey Lee Teh, Chi-Bin Cheng, and Weng Mun Chee. [Identifying and categorising profane words in hate speech](https://dl.acm.org/citation.cfm?id=3193077.3193078). 2018. *ICCDA*
  * Shruti Phadke, Jonathan Lloyd, James Hawdon, Mattia Samory, and Tanushree Mitra. [Framing Hate with Hate Frames: Designing the Codebook](https://dl.acm.org/citation.cfm?id=3274055). 2018. *CSCW*
  * Joni Salminen, Hind Almerekhi, Milica Milenković, Soon-gyo Jung, Jisun An, Haewoon Kwak, and Bernard J. Jansen. [Anatomy of online hate: developing a taxonomy and machine learning models for identifying and classifying hate in online news media](https://www.aaai.org/ocs/index.php/ICWSM/ICWSM18/paper/view/17885). 2018. *ICWSM*
  
  
  #### 2017
  
  * Pinkesh Badjatiya, Shashank Gupta, Manish Gupta, and Vasudeva Varma. [Deep learning for hate speech detection in tweets](https://dl.acm.org/citation.cfm?id=3054223). 2017. *WWW*
  * Haji Mohammad Saleem, Kelly P. Dillon, Susan Benesch, and Derek Ruths. [A web of hate: Tackling hateful speech in online social spaces](https://arxiv.org/abs/1709.10159). 2017. *TA-COS*
  * Eshwar Chandrasekharan, Umashanthi Pavalanathan, Anirudh Srinivasan, Adam Glynn, Jacob Eisenstein, and Eric Gilbert. [You can't stay here: The efficacy of reddit's 2015 ban examined through hate speech](http://comp.social.gatech.edu/papers/cscw18-chand-hate.pdf). 2017. *CSCW*
  * Björn Gambäck, and Utpal Kumar Sikdar. [Using convolutional neural networks to classify hate-speech](http://www.aclweb.org/anthology/W17-3013). 2017. *Workshop on Abusive Language Online*
  * Rijul Magu, Kshitij Joshi, and Jiebo Luo. [Detecting the hate code on social media](https://www.aaai.org/ocs/index.php/ICWSM/ICWSM17/paper/viewPaper/15604). 2017. *ICWSM*
  * Lucas Wright, Derek Ruths, Kelly P. Dillon, Haji Mohammad Saleem, and Susan Benesch [Vectors for counterspeech on Twitter](http://www.aclweb.org/anthology/W17-3009). 2017. *Workshop on Abusive Language Online*
 
 
 
 
 #### 2016
 
 *  Sarah Hewitt, Thanassis Tiropanis, and Christian Bokhove. [The problem of identifying misogynist language on Twitter (and other online social spaces](https://dl.acm.org/citation.cfm?id=2908183). 2016. *WebSci*
 *  Pete Burnap, and Matthew L. Williams. [Us and them: identifying cyber hate on Twitter across multiple protected characteristics](https://epjdatascience.springeropen.com/articles/10.1140/epjds/s13688-016-0072-6). 2016. *EPJ Data Science*
 *  Imran Awan. [Islamophobia on Social Media: A Qualitative Analysis of the Facebook's Walls of Hate](http://cybercrimejournal.com/ImranAwanvol10issue1IJCC2016.pdf). 2016. *International Journal of Cyber Criminology*
 *  Silva, Leandro, Mainack Mondal, Denzil Correa, Fabrício Benevenuto, and Ingmar Weber. [Analyzing the targets of hate in online social media](https://www.aaai.org/ocs/index.php/ICWSM/ICWSM16/paper/viewPaper/13147). 2016. *ICWSM*
 *  Zeerak Waseem. [Are you a racist or am i seeing things? annotator influence on hate speech detection on twitter](http://aclweb.org/anthology/W16-5618). 2016. *NLP and Computational Social Science*
 
 
 
 #### 2015
 
 *  Njagi Dennis Gitari, Zhang Zuping, Hanyurwimfura Damien, and Jun Long. [A lexicon-based approach for hate speech detection](https://preventviolentextremism.info/sites/default/files/A%20Lexicon-Based%20Approach%20for%20Hate%20Speech%20Detection.pdf). 2015. *International Journal of Multimedia and Ubiquitous Engineering*
 *  Shuhua Liu, and Thomas Forss. [New classification models for detecting Hate and Violence web content](https://ieeexplore.ieee.org/abstract/document/7526960/). 2015. *IC3K*
 *  Fabio Fasoli, Anne Maass, and Andrea Carnaghi. [Labelling and discrimination: Do homophobic epithets undermine fair distribution of resources?](https://www.ncbi.nlm.nih.gov/pubmed/25330919). 2015. *British Journal of Social Psychology*
 *  Jamie Bartlett and Alex Krasodomski-Jones. [Counter-speech examining content that challenges extremism online](https://www.demos.co.uk/wp-content/uploads/2015/10/Counter-speech.pdf). 2015 *DEMOS*
 *  Nemanja Djuric, Jing Zhou, Robin Morris, Mihajlo Grbovic, Vladan Radosavljevic, and Narayan Bhamidipati. [Hate speech detection with comment embeddings](https://dl.acm.org/citation.cfm?id=2742760). 2015. *WWW*
 
 
 
 
 #### 2014
 
 *  Jamie Bartlett, Richard Norrie, Sofia Patel, Rebekka Rumpel, and Simon Wibberley. [Misogyny on twitter](https://demos.co.uk/project/misogyny-on-twitter/). 2014. *Demos*
 *  Susan Benesch. [Countering dangerous speech: new ideas for genocide prevention](https://www.ushmm.org/m/pdfs/20140212-benesch-countering-dangerous-speech.pdf). 2014.
 
 
 
  
 #### 2013
 
 *  Irene Kwok, and Yuzhou Wang. [Locate the hate: Detecting tweets against blacks](https://pdfs.semanticscholar.org/db55/11e90b2f4d650067ebf934294617eff81eca.pdf). 2013. *AAAI*
 *  Michal Bilewicz, Mikołaj Winiewski, Mirosław Kofta, and Adrian Wójcik. [Harmful Ideas, The Structure and Consequences of Anti‐Semitic Beliefs in Poland](https://onlinelibrary.wiley.com/doi/full/10.1111/pops.12024). 2013. *Political Psychology*
  
  

#### 2012

* Karmen Erjavec and Melita Poler Kovačič. [“You Don't Understand, This is a New War!” Analysis of Hate Speech in News Web Sites' Comments](https://www.tandfonline.com/doi/abs/10.1080/15205436.2011.619679). 2012. *Mass Communication and Society*

#### 2002

* Vasu Reddy. [Perverts and sodomites: Homophobia as hate speech in Africa](https://www.tandfonline.com/doi/abs/10.2989/16073610209486308). 2002. *Southern African Linguistics and Applied Language Studies*
  
  




### <a name='langGer'> German
  
  
 
 #### 2017
 
 *  Björn Ross, Michael Rist, Guillermo Carbonell, Benjamin Cabrera, Nils Kurowsky, and Michael Wojatzki. [Measuring the reliability of hate speech annotations: The case of the european refugee crisis](https://arxiv.org/pdf/1701.08118.pdf). 2017. *NLP4CMC*
  
  
  
  
  
  
  


### <a name='langIndo'> Indonesian
  
  #### 2017
  
  * Ika Alfina, Rio Mulia, Mohamad Ivan Fanany, and Yudo Ekanata. [Hate speech detection in the indonesian language: A dataset and preliminary study](https://ieeexplore.ieee.org/abstract/document/8355039). 2017. *ICACSIS*
  
  #### 2018
  
  * M. Ali Fauzi and Anny Yuniarti. [Ensemble Method for Indonesian Twitter Hate Speech Detection](http://iaescore.com/journals/index.php/IJEECS/article/view/10638). 2018. *Indonesian Journal of Electrical Engineering and Computer Science*
  
  
  
  
  
  
  
### <a name='langItalian'> Italian
  
  #### 2018
  
  * Manuela Sanguinetti, Fabio Poletto, Cristina Bosco, Viviana Patti, and Stranisci Marco. [An italian Twitter corpus of hate speech against immigrants](https://iris.unito.it/bitstream/2318/1686261/1/710.pdf). 2018. *LREC ELRA*
  
  #### 2017
  
  * Fabio Del Vigna, Andrea Cimino, Felice Dell'Orletta, Marinella Petrocchi, and Maurizio Tesconi [Hate me, hate me not: Hate speech detection on Facebook](http://ceur-ws.org/Vol-1816/paper-09.pdf). 2017. *Italian Conference on Cybersecurity*
  * Fabio Poletto, Marco Stranisci, Manuela Sanguinetti, Viviana Patti, and Cristina Bosco. [Hate speech annotation: Analysis of an italian Twitter corpus](https://iris.unito.it/retrieve/handle/2318/1659197/387293/paper024.pdf). 2017. *CLiC-it*  
  
  
  
  


### <a name='langKenya'> Kenya
  
  #### 2014
  
  * Wilson Jeffrey Maloba. [Use of regular expressions for multi-lingual detection of hate speech in Kenya](https://su-plus.strathmore.edu/handle/11071/2242). 2014. *PhD diss., iLabAfrica*
  
## <a name='video'> Videos
  
  * [Hate Speech Beyond Borders: Nazila Ghanea at TEDxEastEnd](https://www.youtube.com/watch?v=mS-bVsHqCzU). 2012
  * [Motivation behind studying hatespeech](https://www.youtube.com/watch?v=bghTL5gU6fs). 2018
  * [Hate speech and the speech we hate](https://www.youtube.com/watch?v=Fxe80Hglexw). 2019
  
  
  
## <a name='blog'> Blogs
  
  * [No Hate speech Movement](http://blog.nohatespeechmovement.org)
  
  

## <a name='interReads'> Interesting Reads
  
  * Alexandra A. Siegel. [Online Hate Speech](https://alexandra-siegel.com/wp-content/uploads/2018/09/Siegel_Online_Hate_Speech.pdf). 2018.


## TODO's

* Add Abstract and paper's contribution

* Add labels to categorize paper

* Build a Github Page

* A list of papers for Beginners

* Add more papers
  
<!--
## Contact
 --->
