writeCode

Write code to:-

<!-- in mongosh -->

- create a database named `mountains`
<!-- use mountains -->
- a collection inside that database named `himalayas`
<!-- db.createCollection("himalayas") -->
- insert 1 document into that collection `{name: 'Dhauldhar range', height: '4000 mtrs'}`
<!-- db.himalayas.insert({ name: 'Dhauldhar range', height: '4000 mtrs'}) -->
- insert multiple document using insertMany command
  <!-- let rajpoot = [{name:"lalsingh", age:55},{name:"suman",age:50 },{ name:"himanshu",age:22},{name:"ronu",age:26},{name:"ragni",age:24}] -->

- find all documents from mountains
<!-- db.himalayas.find() -->
- find a single document using name
<!-- db.himalayas.findOne({name:"lalsingh"}) -->
