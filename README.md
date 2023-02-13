# E-commerce-backend

# Table of Contents

# Descritption
This E-commerce-backend uses Express, APIs, and MySQL to create a database with models and associations. See how it functions with in the walkthrough video.

# Acceptance Criteria
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

# Installation
- Clone the repository into the terminal
- This requires the use of node.js and MySQL, they must be installed to the computer
- Type npm install or npm i
- Connect to the database usinf the following commands
    - mysql -u root -p
    - when mysql is opened type source schema.sql
    - Then npm run seed (for the seed file)
- Now to run the app type npm start. 
- Finally use insomnia core to see if it is working. Or visit the walkthrough video.


# License
This application uses an MIT license.
# Walkthrough Video:
