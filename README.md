To create a local graphql server on your machine:
Clone this project.
Go to the project and run the project with the code:
    node index.js

In the browser open the URL: http://localhost:4000/

Write the following query:
query booksQuery{
  books{
    title
    author
  }
}

Click on "Play" button.