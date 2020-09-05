# Note-Taker
 

 ## Description of the application

 This application is called Note-Taker , it is used
 
  to write, save and delate notes. It use an express
  
   backend and save and retrive note data from JSON 
   
   file.

This application have a 'db.json' file on the backend

 that used to store and retrive notes using the 'fs' 
 
 module.

It include different HTML routes like 

* GET `/notes` -  return the `notes.html` file.

* GET `*` -  return the `index.html` file. 

It also include API routes 

* GET `/api/notes` - read the `db.json` file and 

return all saved notes as JSON.

  * POST `/api/notes` -  receive a new note to save 
  
  on the request body, add it to the `db.json` file, 
  
  and then return the new note to the client.


  * DELETE `/api/notes/:id` - receive a query 
  
  parameter containing the id of a note to delete. 
  
  This application allow users to create and save 
  
  notes, it allows user to view previously saved 
  
  notes and also allow users to delete previously 
  
  saved notes from thier list.



























HEroku deployed link:

GIthub link:https://github.com/metasabeya/Note-Taker.git

video link: https://drive.google.com/file/d/1qv7-cTUdjLBPwLD25PDTp0lZ3LMTBGQW/view?usp=sharing