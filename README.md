# humlife360-nlp
Transcription and Analysis of Phone Conversations

## Transcription
• Converts audio files to appropriate format (wav) <br/>
• Uses credentials from Google Speech to Text for long audio conversion<br/>
• Uses Indian English language algorithm to transcribe phone conversation recordings for an entire directory<br/>
• Saves results in desired location as .txt files<br/>
• Skips files that are already transcribed

## Phone Conversation Analysis
• Converts transcriptions to TF-IDF vectors<br/>
• Uses unsupervised LDA for topic modeling and visualises result as an interactive HTML<br/>
• Creates wordcloud, gives output as an image<br/>
• Sentiment analysis using NLTK and a lexicon base, shows output as a graph<br/>

## Unsupervised LDA
Uncleaned code for LDA Topic Modeling

## Anchored CorEx
Alternative method for Topic Modeling, may give better results depending on data
