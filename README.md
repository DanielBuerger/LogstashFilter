# LogstashFilter
Logstash filter for data preprocessing and effecient data storage.

## Intention
This is a logstash filter, where you can push json log files and csv log files into your Elasticsearch database. Logstash also gives you 
some tools to preprocess those data thereby reducing the weight of your database. You can modify it for live data feed aswell. 

Be careful to only alter or delete features that your approved before to be not relevant or under dataprotection.

## Commands

push your data from local with linux by using 
```
nc localhost:5000 < /data/data.json
```

## Sources
Logstash Documentation
https://www.elastic.co/guide/en/logstash/current/getting-started-with-logstash.html
