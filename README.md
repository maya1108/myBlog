# Blog
This project is a website that contains blog features , as well as includes a page to display projects
## Prerequisites
npm express,ejs
node.js
## Author
Maya G.
## Database Specifications
The database is used to store  all the articles within the blog in a table named posts. <br />
database: mySQL <br />
 posts table includes the following variables:
 - postid: int , auto increments , not null
 - title: varchar(244) ,not null
  - body: blob , not null
  - date: datetime , set to default  current timestamp
