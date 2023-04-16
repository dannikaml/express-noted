# express-noted


## Description
Express.js application for taking notes

## Usage
***
By utilizing Node.js we can create a command-line application that dynamically generates **************** using the Inquirer package.

To install Universally Unique IDentifiers, please use:

```
npm i uuid
```

The application will be invoked by using the following command:
```
node server.js
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

### Sources

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