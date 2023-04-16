# express-noted


## Description
This is an Express.js application for taking and organizing notes. It's designed to be a simple and intuitive way to keep track of your thoughts, ideas, and to-do lists. With this app, you can create new notes, edit existing notes, and delete notes that you no longer need. Notes are organized in a list view, making it easy to find the note you're looking for. This app is perfect for anyone who wants a simple and efficient way to take and organize notes. 

## Usage
***
To use this app, you'll need to have Node.js installed on your computer. Once you have those installed, you can follow these steps:


Install the necessary dependencies, please use:
```
npm install
```

The application will be invoked by using the following command:
```
node server.js
```
Open your web browser and go to:
```
http://localhost:3001
```

### User Story
```
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
```
## Acceptance Criteria
```
GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
WHEN I enter a new note title and the note’s text
THEN a Save icon appears in the navigation at the top of the page
WHEN I click on the Save icon
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column
WHEN I click on the Write icon in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand col
```

![screenshot](./assets/Screenshot%202023-04-16%20144942.png)

### Sources:

ExpressJs:
- https://expressjs.com/en/guide/routing.html
- https://expressjs.com/en/starter/static-files.html

stackOverflow:
- https://stackoverflow.com/questions/23259168/what-are-express-json-and-express-urlencoded
- https://stackoverflow.com/questions/292965/what-is-a-uuid 

geeksforgeeks:
- https://www.geeksforgeeks.org/node-js-fs-readfile-method/#

mdn docs:
- https://developer.mozilla.org/en-US/docs/Glossary/UTF-8

ChatGPT, 
Instrcutor: Bassie B., 
TA: Ethan D.,
Tutor: Jacob C. 