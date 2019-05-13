# CEU Course 'Automated Text Analysis in Political Science'

This page contains the materials for the short MA political science course *Automated Text Analysis in Political Science* for political science MA students at CEU (6-17 May 2019). Materials will be added as we go along.

Instructor: [Martijn Schoonvelde](http://mschoonvelde.com)

You can find the syllabus [here](Syllabus_CEU.pdf). For any questions, send me an email at mschoonvelde[at]gmail[dot]com.

## Assignments

| Date        | Link           | Answers  |
| ------------- |:-------------:|  -------------:|
| May  10, 19:00h   | [Assignment 1](Assignments/Assignment_1.zip) | [Solutions](Solutions/String_Operations_Answer.pdf) |
| May  15, 13:00h   | [Assignment 2]() | |

## Slides
| Date        | Slides           |  Date        | Slides           |
| ------------- |:-------------:| ------------- |:-------------:|
| May  6   | [Link](Slides/Slides_May_6.pdf) | May  13   | [Link](Slides/Slides_May_13.pdf)|
| May  7   | [Link](Slides/Slides_May_7.pdf) | May  14   | [Link]()|
| May  8   | [Link](Slides/Slides_May_8.pdf) | May  15   | [Link]()|
| May  9   | [Link](Slides/Slides_May_9.pdf)  | May  16   | [Link]()|
| May  10   | [Link](Slides/Slides_May_10.pdf)| May  17   |  Presentations |


## Code practice
| Date        | Link           | Solutions           |    
| ------------- |:-------------:|:-------------:|
| May  6   | Introduction |  |
| May  7   | [Script](Code_Practice/String_Operations.pdf) | [Exercise solution](Solutions/String_Operations_Answer.pdf) |
| May  8   | [Script](Code_Practice/Data_to_DFM.pdf), [Data](Data/speeches_uk.csv.zip) |  [Exercise solution](Solutions/Data_to_DFM_Answer.pdf) |
| May  9   | [Script](Code_Practice/Describing_Text.pdf), [Data](Data/speeches_uk.csv.zip)|  |
| May  10   | [Script](Code_Practice/Dictionaries_and_Supervised_ML.pdf), [Data](Data/speeches_uk.csv.zip)|  |
| May  13   | [Script](Code_Practice/Scaling.pdf), [Data](Data/speeches_ep.csv.zip)|  |
| May  14   | [Script](), [Data]() | |
| May  15   |  Applications  |
| May  16   | Conclusion  |
| May  17  | Presentations | |

### Acknowledgements

For some code in the code practice scripts, I made use of materials by Jos Elkink [here](http://www.joselkink.net/files/POL30430_Spring_2017_lab11.html), and [here](http://www.joselkink.net/files/POL30430_Spring_2017_lab12.html), and Wouter van Atteveldt [here](http://vanatteveldt.com/ccs_lda/) and [here](http://vanatteveldt.com/learningr/). The setup of the code practice scripts follows the structure in Welbers, K., Van Atteveldt, W., & Benoit, K. (2017) (see below for citation). For some slides in week 1 of the course I made use of materials by Pablo Barberá and Ken Benoit [here](https://lse-my459.github.io/). Thanks to all.

## Course schedule
----

*May 6: 15:30 - 17:10:*

* Introduction to the course and to EUSpeech, a dataset which will use for running examples: [Link](https://dataverse.harvard.edu/dataverse/euspeech)
* Required reading:
	* Schumacher, G., Schoonvelde, M., Traber, D., Dahiya, T., & De Vries, E. (2016). EUSpeech: a New Dataset of EU Elite Speeches. In: Proceedings of the International Conference on the Advances in Computational Analysis of Political Text, 75-80.
	* Michel, J.B., Shen, Y.K., Aiden, A.P., Veres, A., Gray, M.K., Pickett, J.P., Hoiberg, D., Clancy, D., Norvig, P., Orwant, J. and Pinker, S., (2011). Quantitative analysis of culture using millions of digitized books. Science, 331(6014), 176–182.
	* Wilkerson, J. and Casas, A. (2017). Large-scale computerized text analysis in political science: opportunities and challenges. Annual Review of Political Science 20: 529-544.

*May 7: 15:30 - 17:10:*

* A survey of automated text analysis in political science. Supervised and unsupervised methods. Validation, validation, validation. Text Analysis in R.
* Required reading:
	* Grimmer, J., & Stewart, B. M. (2013). Text as data: The promise and pitfalls of automatic content analysis methods for political texts. Political Analysis, 21(3), 267-297.
	* Welbers, K., Van Atteveldt, W., & Benoit, K. (2017). Text Analysis in R. Communication Methods and Measures, 11(4), 245-265.
	* Benoit, K., Watanabe, K., Wang, H, Nulty, P., Obeng, A., Mueller, & Matsuo, A. (2018). Quanteda: An R package for the quantitative analysis of textual data. Journal of Open Source Software, 3(30), 774.

*May 8: 15:30 - 19:00:*
* Pre-processing data. Going from text to data, including a few notes of caution. Discussion of the research design and research note.
* Required reading:
	* Denny, M. J., & Spirling, A. (2018). Text preprocessing for unsupervised learning: why it matters, when it misleads, and what to do about it. Forthcoming at Political Analysis.
	* Schoonvelde, M., Schumacher, G. and Bakker, B.N., (2019). Friends with text as data ben- efits: assessing and extending the use of automated text analysis in political science and political psychology. Journal of Social and Political Psychology, 7(1), 124–143.

*May 9: 15:30 - 17:10:*
* Systematically describing and comparing texts.
* Required reading:
	* Chapters 3 and 4 of Silge, J., & Robinson, D. (2018). Text Mining with R: A Tidy Approach. O’Reilly Media, Inc. Available at https://www.tidytextmining.com
	* Cross, J. & Hermansson, H., (2017). Legislative amendments and informal politics in the European Union: A text reuse approach. European Union Politics, 18(4): 581–602.
 	* Bischof, D. & Senninger, R., (2018). Simple politics for the people? Complexity in campaign messages and political knowledge. European Journal of Political Research, 57(2): 473–495.

*May 10: 15:30 - 17:10:*
* Using dictionaries to measure sentiment, happiness and other things we're interested in.
* Required reading:
	* Pennebaker JW & King L (1999) Linguistic styles: language use as an individual difference. Journal of Personality and Social Psychology, 77(6), 1296-1312.
	* Young, L., & Soroka, S. (2012). Affective news: The automated coding of sentiment in political texts. Political Communication, 29(2), 205-231.
	* Kraft, P. (2018). Measuring morality in political attitude expression. Journal of Politics, 80(3): 1028–1033.
	* Hawkins, K. & Castanho Silva, B. (2018). Text Analysis: Big Data Approaches. In: The Ideational Approach to Populism: Theory, Method & Analysis, edited by Kirk A. Hawkins, Ryan Carlin, Levente Littvay, and Cristobal Rovira Kaltwasser. London: Routledge.
	* Ramey, A. J., Klingler, J. D., & Hollibaugh, G. E. (2019). Measuring elite personality using speech. Political Science Research and Methods, 7(1),163–184.

* *17:00: Coding Assignment 1 Due*

*May 13: 15:30 - 17:10:*
* Scaling methods locating text on an underlying (political) dimension. What do they mean? And how do they work?
* Required reading:
	* Slapin JB & Proksch SO (2008) A Scaling Model for Estimating Time-Serial Positions from Texts. American Journal of Political Science 52, 705-722.
	* Hjorth, F., Klemmensen, R., Hobolt, S., Hansen, M. E., & Kurrild-Klitgaard, P. (2015). Computers, coders, and voters: Comparing automated methods for estimating party positions. Research & Politics, 2(2).
* Daniel Schwarz, Denise Traber, & Kenneth Benoit (2017). Estimating intra- 	party preferences: comparing speeches to votes. Political Science Research and Methods 5(2): 379–396.

*May 14: 15:30 - 17:10:*
* Topic models, unsupervised models for summarizing what a text is about.
* Required reading:
	* Blei, D. M. (2012). Probabilistic topic models. Communications of the ACM, 55(4), 77-84.
	* Roberts, M et al.. (2014). Structural Topic Models for Open-Ended Survey Responses. American Journal of Political Science, 58(4), 1064-1082.
* Boussalis, C. & Coan, T. (2016). Text-mining the signals of climate change doubt. Global Environmental Change, 36: 89–100.

*May 15: 15:30 - 19:00:*
* New developments in data: (i) crowd-sourcing data (ii) images as data, (iii) automated speech recognition, (iv) machine translation.
* Required reading:
	* Benoit, K., Conway, D., Lauderdale, B. E., Laver, M., & Mikhaylov, S. (2016). Crowd-sourced text analysis: Reproducible and agile production of political data. American Political Science Review, 110(2), 278–295.
 	* Proksch, S.O., Wratil, C. and W ̈ackerle, J., (2019). Testing the validity of automatic speech recognition for political text analysis. Political Analysis, 1–21
	* De Vries, E., Schoonvelde, M. & Schumacher, G., (2018). No longer lost in translation: Evi- dence that Google Translate works for comparative bag-of-words text applications. Political Analysis, 26(4), 417–430.
	* Torres, M. (2019). Give me the full picture: Using computer vision to understand visual frames and political communication. Working paper.

*May 16: 15:30 - 17:10:*
* New developments in modeling: (i) word embeddings, (ii) ltta
* Flash talks
* Loose ends
* Required reading:
	* Rudkowsky, E., Haselmayer, M., Wastian, M., Jenny, M., Emrich, Sˇ. & Sedlmair, M., (2018). More than bags of words: Sentiment analysis with word embeddings. Communication Methods and Measures, 12(2-3), 140–157.
	* Kleinberg, B., Mozes, M., & van der Vegt, I. (2018). Identifying the sentiment styles of YouTube’s vloggers, EMNLP 2018.

*May 17: 15:30 - 17:10:*
* Research design presentations.

*TBD: Coding Assignment 2 Due*

*TBD: Research Note Due*
