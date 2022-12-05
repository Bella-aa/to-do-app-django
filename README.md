# NotePad

For my **Portfolio 4 Project** on the **Code Institute's Diploma in Software Development (E-commerce Applications)** course I have created a NotePad application where useres can write their to-do lists.

The Note Pad application is an application where users can jot down their tasks or cirtain things they want to achieve in a day or any time. The application is created in such a manner that users can create, view, edit and delete tasks they nolonger want to appear on their note-pad, this gives users the ability to take control of what they want to appear in their notepad.

Link to the deployed app is [here]().

![am I responsive](https://user-images.githubusercontent.com/103276740/205498513-b3d6d19d-e93f-4ee3-bb72-ee5c62446839.png)

-----

## Objective?

-----

The main objective is to create an interactive NotePad website that the owner as a user can engage with via an admin login system to access a database.   The website is created in such a manner that  the user can create, view, edit and delete tasks they nolonger need to appear on their to-do list.

## User Experience

Site Aims
1. To create a Note-Pad website to allow the owner to create new tasks, update existing tasks and delete accomplished tasks .
1. To allow the owner/user to create, view created tasks
1. To allow the owner/user to view or delete tasks they nolonger want
1. To allow the owner to cross out tasks they have already accomplished.
1. To allow users create new tasks
1. To allow new users to create accounts to use Note Pad
1. To allow users to delete their accounts on NotePad if nolonger needed.

## Agile Methodology

* All user stories were entered as issues in a GitHub Kanban project. The live project board can be found on the repository's project tab.

## UX Design

* *The UXD was created taking into consideration "The Five Planes"*

### Strategy plane

* Note Pad applicaction is an app where new users can create new accounts, add items to their to-do list and existing users can log in and add on tasks to their already existing account.

### Scope Plane

* The users will be able to create an account. After logging in, they will be able to add new items/tasks to the to-do list 

### Structure Plane

* Note Pad will have 4 main pages - Login page, Register page,Tasks page and Logout page.

### Skeleton Plane

* Using [Balsamiq Wireframes](https://balsamiq.com/wireframes/), I drew a sketch of how the app will look like, making it easy to follow a pattern while designing the website.

![New Wireframe pp4](https://user-images.githubusercontent.com/103276740/205500288-e30deef1-03aa-41de-8603-bb7279deceaf.png)

### Surface Plane

* The chosen color scheme picked for the website is predominantly blue, white, and purple. 
* The colors of the whole application were chosen to stand out from the main theme to get the attention of the user.
* The color contrast successfully passes using the [a11y](https://color.a11y.com/) contrast. White text over brightly coloured background contrasts well and gives good visual to the user.

-----

# Features

* All features are presented page by page

## Register and Login Page

![Screenshot_20221205_173114](https://user-images.githubusercontent.com/103276740/205703526-64fa0640-256e-4399-ae35-2961c272f8a7.png)
![Screenshot_20221205_173354](https://user-images.githubusercontent.com/103276740/205704014-6c366a04-11c8-4143-995c-291d5fe523d8.png)

* The Login and Register page is the first page the  users will see upon openning the app.
* If the user is already an existing user, they will eneter their login detais and are ready to login into the app.
* If the user is is new, they will register for new account on the register page. User will enter their desired user name and password and their account is setup.

-----

## Tasks Page

![Screenshot_20221205_174101](https://user-images.githubusercontent.com/103276740/205705393-86e00012-f3a9-4f5c-bba6-3f1280a38c59.png)

* This is the page the user will see after loging into the application.
* On this page, the user will see a heading, hello message addressed with their user name.
* On this page users will see buttons and icons they can use to add new tasks to their to-do list.

-----

## Create task page

![Screenshot_20221205_174711](https://user-images.githubusercontent.com/103276740/205706499-6ee01df9-9035-4852-920a-230170726d01.png)

* This is the page where user directed when they want to create a new task
* User will see input fields where they can enter the name and description of their new task 
* User can click save after finishing enetering details and task is saved on the list

-----

## Task delete page

![Screenshot_20221205_175212](https://user-images.githubusercontent.com/103276740/205707680-c4e8422a-dad2-4718-af8f-078fa98ebd34.png)

* This is the page the user is directed to if they decide to delete a task they nolonger wish to appear on their list
* User will see a message to confirm if they really want to delete the task
* User clicks the 'yes, delete' button and task nolonger appears on the list.
* If user decides not to delete task, they can press the back button that appears on top of the page before they confirm deletion.

-----

## Task Search

![Screenshot_20221205_180341](https://user-images.githubusercontent.com/103276740/205709731-19fa19e8-e92f-4524-8b09-58b05e9e1670.png)

* User will see an input field with placeholder text 'search task'
* User will enter key words into the input field and clicks the search task button
* Only tasks with the keywords input will appear after clicking the search task buton.

-----

# Feature Features

* Improve the layout and design of the NotePad application.
* Add a fuctionality to add pictures on the to-do list
* Add a feature to reset username and password if user forgets the old one
* Add functionality to send the user an email confirming they have created an account with NotePad application.

# Technologies Used

* Python
 -The packages installed for the is project can be found in the requirements.txt
* Django
-Django was used as the python framework in the project.
Django all auth was used to handle user authentication and related tasks i.e. sign in, sign up, sign out.
* Heroku
Used to deploy the page and make it publicly available.
* Heroku PostgreSQL
-Used for the database during development and in deployment.
* HTML
-HTML was the base language used to layout the skeleton of all templates.
* CSS
-CSS used to style the page and make the appearance look a little more unique.
* Javascript

# Testing

For this project manual testing was applied:

Constant use of "Run and Debug". This was the most used method of debugging:

* Add a breakpoint to the function currently in test, and check line by line if your variables behaves as intended.
Manual testing occurred regularly throughout local development, making use of statements that would print information to the console and use the Django debug pages.

All links and redirects have been manually tested and all bugs were fixed.

## Lighthouse Testing

* All pages return good performance on desktop and mobile devices.

![Screenshot_20221205_185427](https://user-images.githubusercontent.com/103276740/205719627-acc0914b-36c6-4995-9f90-49c1e096f5b4.png)

# Credits

Thanks to the people who helped me when I got stuck building this project, my mentor , tutor support and the slack community.

## General Reference

Besides the course materail, I also used youtube to reference

## Content

* Content linked from google fonts





 












