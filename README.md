# Enron-network-analysis-Anomaly-detection
The Enron scandal is probably one of the biggest accounting scandals of modern history, and was cited as the biggest audit failure of all times 1. For several years, Enron’s CEO and a team of executives managed to hide billions of dollars in debt from failed deals and projects, especially using poor financial reporting,
accounting ambiguities, ... Some of the executives misled Enron’s board of directors and audit committee on high-risk accounting practices and pressured the accounting firm Arthur Andersen to ignore the issues.
When the issue became public in October 2001, the company declared bankruptcy, and Arthur Andersen, one of the biggest audit and accountancy partnerships in the world, was dissolved.

The goal of this project is to analyze real data, issued from the Enron company, and containing the e-mail exchanges of several people in the company. The project is devided into 2 main part:
1. Network analysis: Build a network graph between employees to find key influencers
2. Anomaly detection: Try to detect abnormal behavior leading up to the public scandal.

The time span goes from April 2000 to June 2002. A detailed version of the data set (including the content of the exchanged e-mails is available at https:
//www.cs.cmu.edu/~enron/). For the project, a smaller and reduced data set is available.

Data
The simplified dataset proposed here contains the email exchanges of 147 persons working at Enron. Only the messages exchanged among those 147 persons were kept from the original data. Email sent to or received from other people were discarded.
The file Enron_events.txt has three columns containing the list of exchanged e-mails : the sender (exped), the receiver (destin), the time instant where the e-mail was sent (time). The time is in seconds and the first event occurs at time 0 which corresponds to 27/04/2000, 01 :19 :00. The last email is sent at 67248094
seconds, corresponding to 12/06/2002, 09 :20 :34.
The file Enron_positions.txt has two columns containing some information on the vertices : the name of the inbox folder of the person, and her position at Enron (if available).
