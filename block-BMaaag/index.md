writeCode

Write code to:-

- create a database named `mountains`
use mountains
- a collection inside that database named `himalayas`
db.createCollection('himalayas')
- insert 1 document into that collection `{name: 'Dhauldhar range', height: '4000 mtrs'}`
db.himalayas.insert({name: 'Dhauldhar range', height: '4000 mtrs'});
- insert multiple document using insertMany command
db.himalayas.insertMany([{name: 'Camera range', height: '1000 mtrs'},{name: 'Shooting range', height: '3000 mtrs'}, {name: 'Mountain range', height: '5000 mtrs'}])
 db.himalayas.find().pretty()
- find all documents from mountains
 db.himalayas.find()
- find a single document using name
db.himalayas.find({name: 'Shooting range'})