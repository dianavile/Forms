# Forms
Create a responsive login/signup form from scratch on a given design.

## Introduction
To become the next Frontend web developer of a Technical Production Team, you have 20 minutes to prove your worth to the CTO and current Frontend Lead developer. Good luck!

## Goals
1. Demonstrate an overall grasp of Web development fundamentals.
2. Talk about your code during the code review.
3. Apply basic WEB technologies: HTML, CSS, Vanilla JavaScript.

## Submission
Push your code to a public repository on your GitHub account.

## Argumentation
A Form is used to: 
- **business**: to store user data (database) into a system.
- **developer**: to **persist** CLIENT data into a SERVER Database (DB).

## Technologies
To create a **login/register form (with CRUD application) based on a given design** (prototype), the application need to use the
 following:

- Apply **HTML5 with BEM (Block Element Modifier) naming conventions**
- Apply **basic CSS styling**.
- Use **JavaScriptJS** in the frontend.

## Features
Your application should have the following **features**:

1. A register form to register users:
   - use email and password to authenticate themselves,
   - input full name when signing in.
   - click on the buttom to register themselves.
2.  Show **validation feedback** when a form is submitted:
   - **see an error message** for an erroneous input in the form.
   - **see a success message** for typing in thecorrect inputs. 
3. The form is **responsive on Mobile, Tablet, Laptop and Desktop**.

**Userstories**:

REGISTERFORM: 
1. Create the layout structure of the User Interface(UI) with HTML tag elements:
- [] HTML-Create `<form>`container
- [] HTML-Add Username & Email `<input>`. 
- [] HTML-Add Submit `<button>.`

2. Add classes to HTML, to style the HTML with CSS classes.
- [] CSS-Style Form class
- [] CSS-Style Input class
- [] CSS-Style Button class

3. Add Javascript to pass data from the CLIENT side to the SERVER side with the HTTP protocol(*the main standard in which a computer CLIENT and SERVER are able to communicate). 
To add new data to a form and store it in a database, the POST operation METHOD of the CRUD* system is needed.

- [] JS-Add onclick
- [] JS-Add validation: error, succes
- [] JS-create functions

4. To make the form behave well on cross-devices: 
make the form responsive with CSS Grid, Flexbox & Media Queries.

- [] Add CSS Grid, Flexbox & Media Queries
- [] Responsive-Design Form Mobile First (1column)
- [] Responsive-Design Form Tablet/Laptop(2column)
- [] Responsive-Design Form DesktopLaptop(3column)

# Resource

- [dCode-How to Build a Login & Sign Up Form with HTML, CSS & JavaScript](https://www.youtube.com/watch?v=3GsKEtBcGTk)

# Things To Remember

- autofocus= focused on PageLoad.
- **BEM**=(Block Elements Modifier) Naming Convention.
  **- HTML protocol**= the main standard in which a computer CLIENT and SERVER are able to communicate.
- There are **4 METHODS** for this HTTP protocol: the **CRUD-system**:
  1.  **CREATE**: To add data to a database(dB): `POST`-method.
  2.  **READ**: To receive data from a db: `GET`-method.
  3.  **UPDATE**: To update existing data from a dB: `PUT`-method.
  4.  **DELETE**: To delete existing data from a dB:`DELETE`-method.
