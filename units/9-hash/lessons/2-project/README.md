# Address book

![image](http://i.imgur.com/HHyng59.jpg)

##Scope

This project inolves implementing the core functionality of a simple client side address book. The objective of this project is for students to practice their skills with hashes and strings.
 
##Before Class

### Prerequisites
Students should only start this project after they have completed the other lessons in the unit.

### Starter code

See [here](starter_code/) for code and [here](https://rawgit.com/ScriptEdcurriculum/curriculum/master/units/9-hash/lessons/2-project/starter_code/index.html) to view.

### Solution code

See [here](https://github.com/ScriptEdcurriculum/solutions/tree/master/units/9-hash/lessons/2-project/solution_code) for code (private).

### Assessment

1. Write do-now based off of [assessments from previous lesson](../../../9-hash/lessons/1-hash/assessments/).

##During Class

###Do Now

1. Attendance: Teacher takes student attendance at www.kinvolved.com
2. Return graded do-now and exit ticket from previous class
3. Do-now quiz

###Opening

What is an address book? What do we use address books for? What kind of information does an address book store?

###Lecture

You are going to build the guts of a basic address book. This address book will contain your contacts. Here are your instructions:

#### 1. `addContacts()`

Modify `js/guts.js` and create a function called `addContacts()`. This function will not take in any parameters. It will return a hash. The hash shall be structed as follows:

* The key of the hash must be your contact's name in string form.
* The value of the hash must be another hash. 
	* This second hash must contain three key-value pairs. The keys must be called: location, picture, and email. The values for each of these keys will be a string.

Populate this hash with 5 contacts. For the picture value, supply a link to the picture in the form of a string. Use image hosting services such as [imgur](http://imgur.com) if you need to.

#### 2. `searchContacts(contacts, query)`

Modify `js/guts.js` and create a function called `searchContacts(contacts, query)`. This function will take in two parameters: `contacts` which is a hash containing the contacts from `addContacts()` and `query` which is the search query of the user. Use `console.log()` to verify that these statements are true.

This function should return a hash containing all the contacts that match the user's search query. You should check the query against every key-value pair. In other words, the user should be able to search for a contact by name, location, or email.

###Brianstorming
Before you start coding, identify the list of steps you need to do to finish this project. Here's a start:

1. Write down your contacts in a separate file. Get their names, locations, emails, and pictures ready.
2. Think about the structure of the hash for `addContacts()`. Review what a hash in a hash looks like from the previous lesson if you need to.
3. Think about how to scan through a hash for `searchContacts()`. 
4. Bring the starter code into your own environment.

###Build Time
Students will work alone on this project. The teacher's role will be to walk around the room helping students with any questions they have. Students are encouraged to look at previous lessons for reference.

##Closing
Select students to present their work to the class.

###Check for Understanding
Teachers should keep track of student success while they are presenting to the class.

###How to Submit
The teacher must ask students to share the link to their project on your school's [Project Submission Form.](https://docs.google.com/a/scripted.org/spreadsheets/d/1kaVH9hmkDCbBul19583UMPxl6IJ3-4pHgBQ2BU6TKDk/edit#gid=0)

Also remind students to add a link to their project on their About Me page.
