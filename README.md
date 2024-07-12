Code Structure
The code is structured as follows:
1.	The HTML code defines the structure of the web page, including the header, body, and different sections of the To-Do List.
2.	The CSS code styles the elements of the To-Do List, including the colors, fonts, and layout.
3.	The JavaScript code handles the functionality of the To-Do List, such as adding tasks, marking tasks as completed, and removing completed tasks.
4.	The code is a simple HTML document with some CSS and JavaScript. It creates a basic HTML document with a heading, meta information, and a link to the fonts used.
5.	The code starts by defining the title of the page as "To do List" and then links to two external stylesheets, one for fonts and another for icons.
6.	The body of the page contains an unordered list that is used to display tasks on this list.
7.	Each task has a number assigned to it so that they can be easily sorted in order from most important to least important. Each item in the list is wrapped in tags which are followed by text inside tags. This text represents what needs to be done or completed on each particular task, such as "buy milk".
8.	This is the container for all of the buttons that are going to be on this page.
9.	It has an ul element inside it, which contains three list elements: "list_work", "list_sport", and "list_music".
10.	The first list element in the ul is called "list_work" and its contents are two links: one link that says “finish action” and another link that says “0”.The second list element in the ul is called "list_sport" and its contents are two links: one link that says “finish action” and another link that says “1”.The third list element in the ul is called "list_music" and its contents are two links: one link that says “finish action” and another link that says “2”.
11.	The code is a part of the "cont_todo_list_top" container.
12.	It is used to create a button that takes you to the bottom of the list.The code starts with a section, which includes the title and links to the stylesheet and icon files.
•	The body of the document contains two paragraphs.The first paragraph has three heading tags. These are used to create different levels of headings in a document.
•	The text between these tags is divided into four blocks, each of which contains one line of code.The first block sets up some basic HTML elements, including the title and links to the style sheet and icon files.The second block defines three heading tags for use in later paragraphs.The third block defines a list item using the tag.
•	This listsitemcontains three lines of text, each preceded by a colon (:).Each line is separated by a space character ( ).
•	Finally, the fourth block sets up some basic formatting for this list item using CSS rules.

The next paragraph starts with two heading tags: 
•	These are used to format different types of text in a document. Between these tags, it defines four blocks of text that contain various pieces of information about this paragraph.
The next section of the code includes some style information for the document. The body of the code contains two paragraphs.
•	The first paragraph explains what is going on in detail while the second paragraph provides an overview of what is to be accomplished.This is the container for all of the content in this page.Inside , there are three different sections: cont_todo_list_top, cont_btns_options, and cont_todo_list. cont_todo_list_top contains a list of items.
•	The first item is a element, which represents an individual task.
•	The second and third items are both elements, which represent links to other pages on the website (in this case, the other two sections).
•	When someone clicks one of these links, it will take them to those other pages.cont_btns_options contains some basic options for how this list works.
•	There are three buttons: "Add Item", "Edit Item", and "Delete Item".These buttons will do different things depending on what you click them with (for example, if you click "Add Item", it will add a new task to the list; if you click "Edit Item", it will open up an editor where you can change the details of an existing task; if you click "Delete Item", it will remove that task from the list).
The first item in the list is for completing an action (in this case, clicking on the i icon), while the other two items are for viewing and listening to music respectively.When the user clicks on the icon, they will be taken to a page that will ask them to input some information about themselves.
Once they have finished filling out the form, they will be redirected back to the main page where they can see their completed action and any errors that occurred along the way.
The code of Javascript is structured into several functions that handle different aspects of the to-do list application. Let's take a closer look at each function:
•	add_to_list: This function is called when the user clicks the "Add" button to add a new task to the list. It retrieves the values entered by the user (action, description, title, and date) and determines the category of the task using a switch statement. It then creates the HTML markup for the task and appends it to the list.
•	finish_action: This function is called when the user clicks the "Finish" button to mark a task as completed. It updates the class of the task element to change its appearance and calls del_finish function after a delay to remove the completed task from the list.
•	del_finish: This function is responsible for removing completed tasks from the list. It selects all task elements with the class "list_finish_state" and animates their removal by changing their opacity, height, and margin. After a delay, it removes the task elements from the DOM.
•	add_new: This function is called when the user clicks the "Add New" button to toggle the visibility of the input fields for adding a new task.
