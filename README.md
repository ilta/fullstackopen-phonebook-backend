# Exercises, part 3

## Server

The server is deployed to [Render](https://fullstackopen-phonebook-backend-7nti.onrender.com/).

## Files

The file structure is as follows:

```
index.js                 main program
tests/                   tests (.rest files for VS Code) for manipulating records
  add_new_person_01.rest normal person addition – may be used for trying to add duplicate persons (should send an error)
  add_new_person_02.rest adding a person with missing name (should send an error)
  add_new_person_03.rest adding a person with missing number (should send an error)
  add_new_person_04.rest adding a person with too short name (should send an error)
  delete_01.rest         removing a person with the id "1" (should fail now)
  update_person_01.rest  normal updating of a person's number
  update_person_02.rest  update a person with missing number (should send an error)
  update_person_03.rest  update a person with invalid number type (should send an error)
```
