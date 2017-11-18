# IntellectAssignment
Spring boot assignment

CREATE USER:
POST http://localhost:8181/users/create
{
  "fName":"kishor",
  "lName":"thakarke",
  "email":"aba.b@gmail.com",
  "pinCode":"12344"
}

========================

UPDATE USER:
PUT http://localhost:8181/users/update
{
  "id":"1_kishor",
  "pinCode":"213"
}
========================

DELETE USER:
DELETE http://localhost:8181/users/delete
{
  "id":"1_kishor"  
}

=========================


