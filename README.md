# Ukraine War and Big Data Tools

## Synopses
This Project utilizes big data tools such as NiFi, HDFS, and PySpark to ingest, query, store, and perform machine learning to predict the outcome type to determine if civilians should flee or if they will be relatively safe to stay. A flow was created in NiFi to ingest the data, query it to select the desired columns/data range, and then return the modified data. HDFS received the data where its storage capabilities were utilized thus being accessible to PySpark. PySpark was used to further clean the data and prepare it for machine learning in which a Decision Tree Classifier was used to achieve an accuracy of 98%.

## Ethical Implications/Notice
While the data does contain protests of varying degrees and battle related data, the distribution between the two is heavily skewed towards battle related data. This project was created for educational purposes only and could result in undesirable consequences if applied.

## References
Ukraine conflict monitor. ACLED. (2024, April 4). https://acleddata.com/ukraine-conflict-monitor/ 
Armed conflict location & event data project codebook. (n.d.). https://acleddata.com/acleddatanew/wp-content/uploads/dlm_uploads/2023/06/ACLED_Codebook_2023.pdf 
