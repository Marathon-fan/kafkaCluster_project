setting up kafka Clusters with zookeepers quorum(distributed with leaders)




## notice    
### zookeeper  
should not do the following anymore    
4 (deprecated)used by old consumer API to store consumer offsets(we should use the new consumer API)    

three zookeepers or five zookeepers??
three zookeepers(suitable for many scenarios)  
five zookeepers(suitble for 100 brokers in kafka)  


## xxxx  
ISR(zookeeper)       in sync replica     
ACL(kafka)           Access Control List

