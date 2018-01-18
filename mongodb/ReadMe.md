CLI Commands:

1. Fetch all records as json

db.getCollection(<collection_name>).find().forEach(printjson); 

ex: db.getCollection('demo').find().forEach(printjson); 
