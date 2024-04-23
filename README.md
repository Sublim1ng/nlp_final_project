## Natural Language Processing for Urgency Levels in Support Ticket Analysis
**Ningyu Han**

### 1. Introduction
We now live in an era dominated by the internet, AI bots, and tech devices. There is no doubt that people are utilizing these tools every day to make life easier. However, technical issues such as bugs and system crashes always happen and can slow our pace down. When those problems arise, the most common way to fix them is to submit support tickets to a technology company. This method is straightforward: you encounter a problem, describe it in a ticket, and send it to the company who can deal with it. Those tickets are more than just complaints; they describe the kinds of problems users face and how urgently they need to be solved. Identifying the urgency level of the tickets and solving the high-priority problems quickly is essential for maintaining high levels of customer satisfaction. One of the effective methods to tackle this problem and assess the urgency level of incoming support tickets is by leveraging Natural Language Processing techniques in spaCy, such as Part-of-speech (POS) Tagging and Term Frequency-Inverse Document Frequency (TF-IDF).

### 2. Data
Kaggle provides an open-source dataset that contains details on more than 48,000 support tickets [13]. The original dataset was provided by a British software company called Endava. It contains information on support tickets from the firm's help desk, each with user messages and pre-assigned labels. These support tickets cover various issues, which include account problems, payment issues, technical issues, etc. Each ticket has detailed information about the title, body text, ticket type, category, sub-category, business service, urgency level, and the impact of the problem mentioned in the ticket.
https://www.kaggle.com/code/aniketg11/support-tickets-classification

### 3. Research Questions
- How can Part of Speech (POS) Tagging be utilized to extract key information from the tickets, such as verbs, nouns, adjectives, and adverbs? How does the frequency of these components relate to ticket urgency?
- How can Term Frequency-Inverse Document Frequency (TF-IDF) be used to identify the importance of the content in the tickets? Can we use the scores to predict the urgency of incoming support tickets?

### 4. Content Description
- 01_pos_tagging.ipynb: This notebook contains all the codes, visualizations, and outcomes to answer the first research question.
- 02_tf_idf.ipynb: This notebook all the codes, visualizations, and outcomes to answer the second research question.
- data_ticket.csv: The raw data used in this project.
