# Character-manager-js

Project creat and manage by [**Sebastien Voos**](https://github.com/VOOSsebastien) & [**Olivier d'Ardenne**](https://github.com/MrOlivierdA)

## About this project:

| Challenge Parameters | Challenge Details           |
| :------------------- | :-------------------------- |
| Repository           | `character-manager-js`      |
| Challenge type       | `consolidation challenge`   |
| Duration             | `5 days`                    |
| Deployment method    | `GitHub pages` or `Netlify` |
| Group composition    | `Duo`                       |

## Objectives

- Use best JS practices
- Read documentation and test a REST API
- Use a REST API with HTTP requests
- Create a typical asynchronous flow : send asynchronous (promises or async/await) requests to a remote server and process the results
- DOM manipulation: changing the DOM based on results of HTTP requests

## The job

A Comics fan client would like to manage his favorites characters on a dashboard. He contacts you to create an app that will be able to view, edit, create all his favorites characters.

In this project, you will use the [**Character Database API**](https://character-database.becode.xyz/) to make/fetch a Character Manager. This project ask you to perform HTTP Request.

The root endpoint of the API is the following : https://character-database.becode.xyz/

This is a frontend project, you have to care about the appearance of your application and create a custom template.

### The features

#### Characters list page

This page will be the first one displayed when you open the app. Display the list of all the characters contained inside the database. You can use a table or a list of cards to display them, at your convenience.

Make sure the following features will be present for each character:

- Name
- A short description. Be aware that the `description` field is in Markdown and, of course, we want to display it as HTML in your application.
- An image. **Hint**: [Data URIs](https://css-tricks.com/data-uris/)
- A button to create a new character
- A way to open the corresponding Character

#### Single character

This page should display:

- The name and image for the character.
- A **full description** of the character. Be aware that the `description` field is in Markdown and, of course, we want to display it as HTML in your application.
- A way to open the Character editor
- A way to delete the character (You **must** add some kind of confirmation, like "Are you sure you want to delete this character ?")

#### Character creation

When we click on the character creation button in the Characters list page, we should get redirect to this page. This page should contain a form with an input for each of the following fields:

- `name`
- `shortDescription`
- `image` **Hint**: [Reading local files in JavaScript](https://www.html5rocks.com/en/tutorials/file/dndfiles/)
- `description` (You can just let the user enter Markdown but a Wysiwyg editor generating Markdown would be much cooler)

When the form is completed create the character in the API and redirect to the character list page.

#### Character editor

This part should be similar to the Character creation page except it allows to edit an existing character.  
It should also contain a button to delete the character. When this deleting an item, display a modal asking for confirmation.

#### Search input (optionnal)

The client can search a character by name or by ID.

## Constraints

- Your website must be deployed somewhere. We recommend [Github Pages](https://pages.github.com) or [Netlify](https://www.netlify.com), two great (and free) solutions.
- You have to use the best practises in JS, as much as possible 👉 [Read these instructions](jsbestpractises.md)
- You must use Sass.

---

![](https://media.giphy.com/media/tliXLSkzfq2C4/giphy.gif)
