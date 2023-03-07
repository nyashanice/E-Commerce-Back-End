# E-Commerce-Back-End

## Description

The E-Commerce Back End application provides retail owners a way to access their inventory and compete with other companies in terms of efficiency. I think it is very useful as it's easy to use and gives you a lot of important information. Having this ease of access allows business owners to spend more time on other tasks.

While building this application, I learned about object relational mapping (ORM) and Sequelize associations.

## Installation

To begin using the application, it can be started by entering the `db` folder and starting `mysql` followed by `SOURCE schema.sql`. Next, by entering the server.js terminal and running `npm run seed` and `node server.js` the server should be up and running!

## Usage

To use the application, you can use GET, POST, PUT and DELETE routes in Insomnia. To use the data, you will direct to `localhost:3001/api/products`, `localhost:3001/api/categories`, or `localhost:3001/api/tags` accordingly. A GET route will return all data for that table. If you enter `localhost:3001/api/products/2` for example, it will only return the data for the product with an id of 2.

A POST route can be used to add new data, a PUT route can be used to update existing data, and a DELETE route can be used to remove data.

Watch demo video here: <https://drive.google.com/file/d/1xAALwNfZ1sRWu-xnMy3nOetCyFpudrUT/view>
