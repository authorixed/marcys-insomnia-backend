# marcys-insomnia-backend
In this project, we created a backend server for an e-commerce website. This project stores most of the data necessary to control it.


## User Story
AS A manager at an internet retail company <br>
I WANT a back end for my e-commerce website that uses the latest technologies <br>
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
GIVEN a functional Express.js API <br> 
WHEN I add my database name, PostgreSQL username, and PostgreSQL password to an environment variable file <br>
THEN I am able to connect to a database using Sequelize <br>
WHEN I enter schema and seed commands <br>
THEN a development database is created and is seeded with test data <br>
WHEN I enter the command to invoke the application <br>
THEN my server is started and the Sequelize models are synced to the PostgreSQL database <br>
WHEN I open API GET routes in Insomnia Core for categories, products, or tags <br>
THEN the data for each of these routes is displayed in a formatted JSON <br>
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core <br>
THEN I am able to successfully create, update, and delete data in my database <br>