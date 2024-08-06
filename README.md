# Applied Data Science for Security Professionals
<img src="img/GTK_Logo_Social Icon.jpg" width="175" align="left" >

### 2024 Trainings presented by GTK Cyber

GTK Cyber [www.gtkcyber.com](https://www.gtkcyber.com) was founded to bridge the gap between Data Science and Cyber Security and not
only provide high standard hands-on trainings, but introduce students to the most cutting-edge technologies and advancements in artificial intelligence,
all with a focus on direct applicability to cyber security.



### Centaur Data Science Virtual Machine

In order to have the best student experience, we strongly encourage you to download the Centaur VM here: [https://github.com/gtkcyber/centaur](https://github.com/gtkcyber/centaur).
Centaur is a environment for data science. Centaur is based on Ubuntu MATE and includes numerous data science tools, all installed and configured for immediate use.


### Instructors

- Charles Givre - Data Scientist:  charles.givre@gtkcyber.com
- Summer Rankin - Instuctor & Data Scientist: summer@gtkcyber.com

### Lectures:

<a href="slides/">/Slides</a>
- Introduction
- Exploratory Data Analysis in 1 Dimension
- Exploratory Data Analysis in 2 Dimensions
- Data Visualization
- Machine Learning (Feature Engineering)
- Machine Learning (Supervised)
- Machine Learning (Unsupervised)
- Anomaly Detection
- Hunting with Data Science
- Hacking Machine Learning Models


#### GitHub Structure

- answers (answers notebooks/solutions to all exercises and more)
- data (all data files)
- img (logo and screenshots)
- notebooks (all exercises)
- slides (all slides as pdf)

### Development Environment


**Starting Jupyter notebook**: Go to Applications > Programming > Jupyter Notebook or hit the Nb icon located at the top menu bar. Navigate through your file system and open files with .ipynb extension.

<img src="img/griffon-open-jupyter.png" width="300">

**Starting Zeppelin notebook**: Go to Applications > Programming > Zeppelin > Start Zeppelin > open Mozilla web browser > http://localhost:8060/#/ or hit the Zeppelin icon (takes a while to start up) > import JSON to view notebook.

<img src="img/griffon-open-zeppelin.png" width="300">

**Copy files into VM**: Drag and drop files or folders. You will find them under Filesystem > tmp > VirtualBox Dropped Files > subfolders ...

<img src="img/griffon-dropped-files.png" width="300">


All exercises either as jupyter notebooks (.ipynb) or Zeppelin notebook (.json) are listed below.
Solutions to all challenges are within the ```answers``` folder (also contains additional notebooks and resources).  The worksheets are numbered so that the first number references the module and the second number refers to the position in the module.  For example, the second worksheet in module 1 is Worksheet 1.2.  

Notebooks/Scripts/Exercises and Data

### [notebooks](./notebooks)
    
- Worksheet 1.1 - Working with One Dimensional Data.ipynb
- Worksheet 1.2 - Exploring One Dimensional Data.ipynb
- Worksheet 2.1 - Working with Two Dimensional Data.ipynb
- Worksheet 2.2 - Exploratory Data Analysis.ipynb
- Worksheet 3.0 - Data Visualization.ipynb
- Worksheet 4.0 - Feature Engineering.ipynb
- Worksheet 5.1 - DGA Detection using Supervised Learning.ipynb
- Worksheet 5.2 - DGA Making Predictions on New Data.ipynb
- Worksheet 5.3 - Tuning your Classifier.ipynb
- Worksheet 5.4 - Automate it All!.ipynb
- Worksheet 6.0 - Clustering.ipynb
- Worksheet 7.0 - Anomaly Detection.ipynb
- Worksheet 8.0 - Hunting with Data Science.ipynb
- Worksheet 9.0 - Featureless Deep Learning URL.ipynb
- Worksheet 10.1 - Using AI for Anomaly Detection.ipynb
- Worksheet 10.2 - Exploratory Data Analysis with AI.ipynb
- Worksheet 11.0 - Attacking AI.ipynb

### [answers](./answers)

- Worksheet 1.1 - Working with One Dimensional Data - Answers.ipynb
- Worksheet 1.2 - Exploring One Dimensional Data - Answers.ipynb
- Worksheet 2.1 - Exploring Two Dimensional Data - Answers.ipynb
- Worksheet 2.2 - Exploratory Data Analysis - Answers.ipynb
- Worksheet 3.0 - Data Visualization - Answers.ipynb
- Worksheet 4.0 - Feature Engineering - Answers.ipynb
- Worksheet 5.1 - DGA Detection using Supervised Learning - Answers.ipynb
- Worksheet 5.2 - DGA Making Predictions on New Data-Answers.ipynb
- Worksheet 5.3 - Tuning your Classifier - Answers.ipynb
- Worksheet 5.4 - Automate it All! - Answers.ipynb
- Worksheet 6.0 - Clustering - Answers.ipynb
- Worksheet 7.0 - Anomaly Detection - Answers.ipynb
- Worksheet 8.0 - Hunting with Data Science - Answers.ipynb
- Worksheet 9.0 - Featureless Deep Learning URL - Answers.ipynb
- Worksheet 10.1 - Using GPT for Anomaly Detection - Answers.ipynb
- Worksheet 10.2 - Exploratory Data Analysis with AI - Answers.ipynb
- Worksheet 11.0 - Attacking AI - Answers.ipynb

    
    
## [bonus](./bonus)

   - Module 0.5 [Overview of Regular Expressions.pdf](./bonus/Module%200.5%20Overview%20of%20Regular%20Expressions.pdf)
   - Worksheet 0.1 - [Regular Expressions in Python.ipynb](./notebooks/Worksheet%200.1%20%20Regular%20Expressions%20in%20Python.ipynb)
   - Worksheet 0.1  Regular Expressions in Python - Answers.ipynb
   - Worksheet 8.0 - Zeppelin - PySpark Malicious URL ML Classification - Answers.json ```(open Zeppelin notebook and import JSON to view)```
   - Worksheet 9.0 - Featureless Deep Learning URL - Answers.ipynb
   - Worksheet 11.0 - Zeppelin Part1 - PySpark + ELK + Kafka - Answers.json ```(open Zeppelin notebook and import JSON to view)```
   - Worksheet 11.0 - Zeppelin Part2 - PySpark + ELK + Kafka -Answers.json ```(open Zeppelin notebook and import JSON to view)```

### Recommended Readings

   - [Python for Data Analysis](http://shop.oreilly.com/product/0636920023784.do)
   - [Data Science for Business](http://shop.oreilly.com/product/0636920028918.do)
   - [Creating a Data-Driven Organization](http://shop.oreilly.com/product/0636920035848.do)
   - [Data-Driven Security](http://datadrivensecurity.info/)
   - [Mastering Machine Learning with scikit-learn](https://www.packtpub.com/big-data-and-business-intelligence/mastering-machine-learning-scikit-learn)
   - [Hands-On Machine Learning with Scikit-Learn and TensorFlow](http://shop.oreilly.com/product/0636920052289.do)
   - [Learning Apache Drill](https://amzn.to/2M8Peo6)
   - [Deep Learning](http://www.deeplearningbook.org/)
    
### [data](./data)

- logs/
- access
- attack-trace.pcap
- baltimore_salaries_2015.csv
- baltimore_salaries_2015.csvh
- baltimore_salaries_2015.json
- baltimore_salaries_2016.csv
- baltimore_salaries_2016.csvh
- baltimore_salaries_2016.json
- columns.json
- CountVectorizer_domains.pickle
- CountVectorizer_paths.pickle
- CountVectorizer_tlds.pickle
- cpu-full-a.csv
- cpu-full-b.csv
- cpu-test-a.csv
- cpu-test-b.csv
- cpu-train-a.csv
- cpu-train-b.csv
- customer_data.csv
- customers.json
- d_common_en_words.pickle
- dailybots.csv
- dailybots.csvh
- data1.json
- data2.json
- data3.json
- data4.json
- dates.csv
- dates.csvh
- deeplearning_1DConv.h5
- deeplearning_1DConv.json
- deeplearning_1DConvLSTM.h5
- deeplearning_LSTM.h5
- deeplearning_LSTM.json
- dga_data_full.csv
- dga_data_small.csv
- dga_features_final_df.csv
- dga-full.csv
- domains_created_db.csv
- elonmusk_tweets.csv
- eve_small.json
- eve.json
- FAOSTAT_data_6-25-2019.csv
- feature_names.pickle
- firewall.ssdlog
- firewall1.ssdlog
- google-10000-english.txt
- hackers-access.httpd
- http-pcap.json
- http.pcap
- index.json
- maccdc2012_00000_small.csv
- maccdc2012_00000_small.csv.gz
- maccdc2012_00000_small.pcap.gz
- our_data_dga_features_final_df.csv
- people.csv
- people.csvh
- records.json
- small-server-log.httpd
- split.json
- telnet-cooked.pcap
- twitter1-small.csv
- url_data_full.csv
- url_data_medium.csv
- url_data_mega_deep_learning.csv
- url_data_small.csv
- urls.txt
- user-agents.csv
- values.json
- visualization_data.csv
