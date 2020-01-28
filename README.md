# coronaTrackerNLP
corona tracker related news ( name entities + sentiment ) for english and chinese

## steps
- extact data from MySQL DB (which contains news )
- run text processing and name entity extraction, sentiment analysis
- save the result to MySQL


## demo tableau dashboard link
https://public.tableau.com/profile/lutherteh#!/vizhome/coronaTrackerNLPEntitiesSentiment/CoronaTrackerEntitiesSentiment

## reference 
- spacy https://github.com/explosion/spaCy
- vaderSentiment https://github.com/cjhutto/vaderSentiment
- Jieba (chinese NLP) https://github.com/fxsjy/jieba
