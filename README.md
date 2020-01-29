# coronaTrackerNLP ( ver1.0)
corona tracker related news ( name entities + sentiment ) for english and chinese

## steps
- query data from MySQL (which contains news )
- run text processing and name entity extraction, sentiment analysis
- save the result to MySQL


## demo tableau dashboard link
https://public.tableau.com/profile/lutherteh#!/vizhome/coronaTrackerNLPEntitiesSentiment/CoronaTrackerEntitiesSentiment

## reference 
- spacy https://github.com/explosion/spaCy
- vaderSentiment https://github.com/cjhutto/vaderSentiment
- Jieba (chinese NLP) https://github.com/fxsjy/jieba
