# Book Record Management System:

## Routes and Endpoints

### /user
POST: Create a nerw user
GET: Get all the list of users

## /users/{id}
GET: Get a user by ID
PUT: Update a user by thier ID
DELETE: Delete a user by ID (check if he or she still has an issued book && is there any fine to be paid)

### /user/subscription-details/{id}
GET: Get user subscription details:
>>Date of subscription
>>Valid till
>>Fine if any

### /books
GET: Get all the books
POST: Create a new book
PUT: Update a book by ID

### /books/id
GET: Get a book by ID
PUT: Update a book by ID

### /book/issued
GET: Get all issued books

### /books/issued.withFine
GET: Get all issued books with fine

### Subscription Type:
>> basic(3 months)
>> standard(6 months)
>> premium(12 months)

# Cmds
>>npm init
>> npm i express
>> npm i nodemon --save-dev
