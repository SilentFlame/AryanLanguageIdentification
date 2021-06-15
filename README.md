# Aryan Language Identification
A DNN based model for detection of different dialects of Indo-Aryan languages like Hindi, Magahi, Bhojpuri, Braj, etc.


## Dataset: ##
The 'Data' directory in this repository contains the dataset used for Indo-Aryan Language identitifcation Shared Task as part of the Evaluation Campaign in the Fifth Workshop on NLP for Similar Languages, Varieties and Dialects (VarDial) at COLING 2018.

This task was aimed at identifying 5 closely-related languages of Indo-Aryan language family – Hindi (also known as Khari Boli), Braj Bhasha, Awadhi, Bhojpuri and Magahi. These languages form part of a continuum starting from Western Uttar Pradesh (Hindi and Braj Bhasha) to Eastern Uttar Pradesh (Awadhi and Bhojpuri) and the neighbouring Eastern state of Bihar (Bhojpuri and Magahi). For this task, participants were provided with a dataset of approximately 15,000 sentences in each language, mainly from the domain of literature, published over the web as well as in print. It is the first dataset that is being made available for these languages (except Hindi) and it will not only be useful for automatic identification of languages and developing NLP applications but will also help in gaining insights into the proximity level of these languages (which are hypothesised to form part of a continuum and lot of times mistaken as varieties of Hindi, especially outside the scholarly linguistic circles).

## Details about Dataset ##
The directory 'Data' contains 3 files - the ones used for training, development / validation and testing in the shared task. Each file contains data in one sentence one line format with the language ID separated by a TAB. The langauge IDs are the ISO codes of the respective languages and should be read as below -

AWA = Awadhi

BRA = Braj

BHO = Bhojpuri

MAG = Magahi

HIN = Hindi
