# NotesApp
Description of the app : It implements RESTful API webservice which is responsible for managing and storing in database simple notes (without the UI part). Webservice accepts HTTP calls for creating, reading, updating and deleting notes (CRUD).


### **Technology used:-**
Node js + Express js + MySql


### **Required node packages:-**
npm
moment
express
mysql

### **For Database setup:**

Please run the attached sql script file on mysql workbench

#### **For DB connetion go to   NotesApp\routes\notes.js and inside this file add databese details**

eg:-
host: 'localhost',
user: 'root',
password: '',
database: 'test'


#### **For runnig the project go to the main directory containing 'app.js' and run the following command-:**

npm run


#### **API endpoints for testing the app:-**

for get all notes
get- http://localhost:3000/notes/api/getNotes

for post/create notes
post- http://localhost:3000/notes/api/insertNotes

for update the notes
put- http://localhost:3000/notes/api/updateNotes/id

for select perticular note
get- http://localhost:3000/notes/api/getById/id

for deleting the note
delete- http://localhost:3000/notes/api/deleteById/id

for notes history
get- http://localhost:3000/notes/api/history/id




