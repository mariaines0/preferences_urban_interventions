# preferences_urban_interventions

**1.** This repository is a result of the data collected and the analysis conducted for a paper under review titled "Perceptions of Urban Change: Exploring Before-and-After Visual Preferences for Mobility" (Lopes, M. I., Valença, G., Moura, F.). It aims to be totally open-source for replication purposes.

**2.** The online survey, developed in Limesurvey,  remains available at the following link (https://ushift.tecnico.ulisboa.pt/~ushift.daemon/limesurvey/index.php/562461?lang=en), and participants are still welcome to complete it and explore its interactive, panoramic and innovative format. The survey can be briefly resumed by the following: 


 &nbsp;&nbsp; **2.1** Participants were asked to **select their preferred urban space** from a pair of panoramic and interactive street view images from _Google Street View_, representing the before and after a given intervention, with the ability to navigate and explore each scenario.  
 &nbsp;&nbsp; **2.2** They were also also asked to grade seven perceptual factors in a 5-Point Scale by level of influence in the previous choice. These perceptual factors are _comfort_, _order_, _livability_, _security_, _safety_, _usefulness_ and _stress_.  
 &nbsp;&nbsp;**2.3** Answer to 15 questions about their: (a) **socio-demographics**:  age, gender, number of children, age of children, disability, pets, occupation, city of residence, nationality; (b) **background on urban planning**; (c) **travel behavior**:  commute modes, commute time, car ownership, parking availability 


All interventions (pairs of before-and-after images) explored (embedded in the survey) are available in my Notion profile: https://www.notion.so/Survey-Groups-211188b0f7a980f7b1faf96b14d1a42e?source=copy_link

Before diving into the repository, you should read this:   
(1) The raw dataset from the survey is available in _data_raw_188.csv_ and countries data in _countries_answers_188.csv_.   
(2) The _city_metro_v2.csv_ was created to categorize cities of residence collected in     
 &nbsp;&nbsp;(a) _metropolitan_ or _non-metropolitan_, according to Eurostat metropolitan typology and  
 &nbsp;&nbsp;(b) small town/village; medium-sized city/outskirts/suburban city and large city according to population size


 FIRST STEP: Cleaning Data (_0_clean.ipynb_)
 1. You need inputs _data_raw_188.csv_ and _countries_answers_188.csv_ for 0_clean.ipnyb
 2. Output: data_clean.csv (also directly available in the respository)

SECOND STEP: Encoding Data (_1_encoding.ipynb_)
1. You need inputs _data_clean.csv_, _city_metro_v2.csv_ (with city size and metropolitan classification) and _content_v2.csv_ (which categorizes each image)
2. Output: _data_encoded.csv_

THIRD STEP: Exploratory Data Analysis (_2_EDA.ipynb_) 
1. 

FOURTH STEP: Logistic Regression Modelling (_3_Logit_Model.ipynb_) 
1.

