# EcoSafe
 AI-Enhanced Social Media Platform for Toxic Comment Prevention
 
 The idea behind the project is to address more toxicity online by creating an AI-driven web-based 
platform that spots and removes offensive comments in real time. It would review and block any 
harmful or offensive remarks before they are made public, to guarantee better online conversations 
and care for users’ interests. 
User interface, backend API, machine learning model layer, and database system are all part of the 
architecture’s multi-layer system. Creating an account, logging in, customizing a profile, and posting 
comments are available on the platform as well as using the inbuilt toxic detection system. Machine 
Learning model Support Vector Machine (SVM) is the engine used by this system. A total of more 
than 95,000 comments were used in training the model by combining public datasets (from Kaggle 
and GitHub) and new data contributors added. Processes involved in preprocessing the data are case 
normalization, lemmatization, elimination of special characters, and taking out stopwords from the 
words. To increase the models’ accuracy, feature engineering changes the multi-label data into 
binary classification format. Once the data is preprocessed, it is used to develop and review machine 
learning model according to how they perform based on accuracy, precision, recall, and f1-score. 
The user interface in React.js and CSS ensures that the platform can be easily used on any screen 
with pages such as login screens, account dashboards, form for signing up, commenting, and 
managing profiles. For the API, backend code is written in Flask, and Node.js/Express.js takes care 
of talking with users and response to data requests. The data from users and logs of comments are 
stored in MongoDB as the main database. 
All in all, the project adds artificial intelligence tools to a social media platform, making it easier for 
users to avoid online harm. Later additions will be transformer models for more detailed context, 
working in multiple languages, emoji recognition, and a stronger ability to detect sarcasm and mild 
forms of toxicity.
