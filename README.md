# [Finals Lab Task 6 - MongoDBCRUD](https://github.com/user-attachments/files/20244038/pangilinan_MongoDB.Practice.Task.docx)

This task focuses on performing fundamental MongoDB operations such as creating a database, inserting documents, and executing find, update, search, and delete actions within a collection.

## Step by Step Process

### Create a Database
- Start by creating or switching to a specific database
- The selected database becomes the active workspace for all upcoming operations

### Insert Documents
- Within the database, a collection is created
- Multiple documents are inserted into the collection, each containing structured data fields such as name, age, or address

### FIND Documents
- Display all documents stored in the collection
- Use filters to find specific documents based on certain values like name or ID

### UPDATE Documents
- Locate the document that needs modification using a condition (e.g., name or ID)
- Specify the field(s) to be changed and apply the update
- Confirm the update by checking the document again

### SEARCH Documents
- Use specific criteria to locate documents that match particular conditions (e.g., age greater than a value or status equals a specific string)
- Review the matched results for accuracy

### DELETE Documents
- Identify the document(s) to be removed using a condition
- Remove the document(s) from the collection
- Verify deletion by checking the collection contents

## Queries

## Create Database
![image](https://github.com/user-attachments/assets/b56c32d2-ad0c-4704-a811-fb05223afa46)

## Insert Documents
![image](https://github.com/user-attachments/assets/e99acd48-dea8-4c0b-ac5f-1147d2e4be7a)
![image](https://github.com/user-attachments/assets/cdf30409-f378-49b4-9c29-f4d725223c76)
![image](https://github.com/user-attachments/assets/eec76cd8-508a-425f-8a30-927c0b73a549)
![image](https://github.com/user-attachments/assets/1dd84f52-af1c-47b2-b1fa-c0ba1a25053f)

## get all documents
![image](https://github.com/user-attachments/assets/a46973ab-d652-4e0f-a2e3-8fb656fd277e)
![image](https://github.com/user-attachments/assets/5b6f52fe-ea80-4d63-b1be-96468e3ab664)
![image](https://github.com/user-attachments/assets/bbe789d8-b7a4-4891-8268-61324133847f)

## get all documents with `writer` set to "Quentin Tarantino"
![image](https://github.com/user-attachments/assets/70f2851f-e672-4ce5-b5ca-261fa7ee5853)

## get all documents where `actors` include "Brad Pitt"
![image](https://github.com/user-attachments/assets/ef12a9b6-2eac-4319-a181-1572514a3488)

## get all documents with `franchise` set to "The Hobbit"
![image](https://github.com/user-attachments/assets/e72ce0f9-8e8a-490c-b2c1-33848c7ae781)

## get all movies released in the 90s
![image](https://github.com/user-attachments/assets/749a5512-cd0f-40ed-a02a-929c7f500aec)

## get all movies released before the year 2000 or after 2010
![image](https://github.com/user-attachments/assets/7296b07e-ead9-410d-b7f8-ef03ec2f78aa)

## add a synopsis to "The Hobbit: An Unexpected Journey" 
![image](https://github.com/user-attachments/assets/bd7ba3aa-5584-49ed-bac6-4a87b405545f)


## add a synopsis to "The Hobbit: The Desolation of Smaug" 
![image](https://github.com/user-attachments/assets/e86e56e2-1ca1-4823-8423-8e78d740b79d)


## add an actor named "Samuel L. Jackson" to the movie "Pulp Fiction"
![image](https://github.com/user-attachments/assets/a9d8caa9-46c3-462d-bf81-ef1c469a596e)


## find all movies that have a synopsis that contains the word "Bilbo"
![image](https://github.com/user-attachments/assets/445865ba-36cf-407e-9abe-eb0f4acde048)


## find all movies that have a synopsis that contains the word "Gandalf"
![image](https://github.com/user-attachments/assets/27e92f5a-5063-4255-ae00-d28977b10e27)


## find all movies that have a synopsis that contains the word "Bilbo" and not the word "Gandalf"
![image](https://github.com/user-attachments/assets/79f28fb8-152a-41e4-a59d-f429f0bb0096)


## find all movies that have a synopsis that contains the word "dwarves" or "hobbit"
![image](https://github.com/user-attachments/assets/bce60dcb-18bf-4666-8375-b1b3e2caed6e)


## find all movies that have a synopsis that contains the word "gold" and "dragon"
![image](https://github.com/user-attachments/assets/735d2e46-2b78-4efe-9fb9-e1ca7247a84d)


## delete the movie "Pee Wee Herman's Big Adventure"
![image](https://github.com/user-attachments/assets/05d4eb12-a82a-4c73-b28c-19b0c507b3d5)


## delete the movie "Avatar"
![image](https://github.com/user-attachments/assets/c50bd760-6fd3-4749-b342-78c7021d1627)

## Insert the following documents into a 'users' collection
![image](https://github.com/user-attachments/assets/3a3d7a44-ae53-4812-80c4-0454e4b650dd)

## Insert the following documents into a 'posts' collecton
![image](https://github.com/user-attachments/assets/d83109d2-e938-4741-861e-45bc8d69664f)

## Insert the following documents into a 'comments' collection
![image](https://github.com/user-attachments/assets/c6103663-1226-4601-ac6a-e361be5eab06)

## find all users
![image](https://github.com/user-attachments/assets/69cd9278-8231-4a05-a191-6be3461e726e)

## find all posts
![image](https://github.com/user-attachments/assets/5fc1539a-c84f-4693-ba13-78f1b11bdbef)
![image](https://github.com/user-attachments/assets/16106ec1-d2bf-4468-bc2c-93d7154910d6)

## find all posts that was authored by "GoodGuyGreg"
![image](https://github.com/user-attachments/assets/2523cf87-4556-4fd1-97ae-4254fb2f786e)

## find all posts that was authored by "ScumbagSteve"
![image](https://github.com/user-attachments/assets/7419cd0e-c45f-495b-81fd-541088406c93)

## find all comments
![image](https://github.com/user-attachments/assets/d65f5bdc-ecdb-4e2f-afbd-ad56c959e570)
![image](https://github.com/user-attachments/assets/9d3e5b8c-309c-4b33-a570-370aa925b7bf)

## find all comments that was authored by "GoodGuyGreg"
![image](https://github.com/user-attachments/assets/326b0a86-319d-4fa4-a98b-9a8a0c6c2146)

## find all comments that was authored by "ScumbagSteve"
![image](https://github.com/user-attachments/assets/e7198777-2e45-4354-98a1-b3e55faea105)

## find all comments belonging to the post "Reports a bug in your code"
![image](https://github.com/user-attachments/assets/5430ff35-e663-431f-898c-121fc552ee47)

## ER Diagram
![image](https://github.com/user-attachments/assets/0bce4b7a-3217-416a-b8ab-5b0f6c06c1e1)










