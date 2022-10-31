# ecommerce-backend

Backend for e-commerce site.

## Installation

To install necessary dependencies, run the following command:

```sh
npm install
```

## Usage

- Create the required schema by sourcing `schema.sql` in `db` folder.
- Create a `.env` file in the root directory and define the following variables: `DB_USER`, `DB_PW` and `DB_NAME`.
- Run `npm start` to start the application.

The following API calls are supported:

### Categories

- Get all categories: `GET /api/categories`
- Get category by id: `GET /api/categories/:id`
- Add a category: `POST /api/categories`
- Update a category: `PUT /api/categories/:id`
- Delete a category: `DELETE /api/categories/:id`

### Products

- Get all products: `GET /api/products`
- Get product by id: `GET /api/products/:id`
- Add a product: `POST /api/products`
- Update a product: `PUT /api/products/:id`
- Delete a product: `DELETE /api/products/:id`

### Tags

- Get all tags: `GET /api/tags`
- Get tag by id: `GET /api/tags/:id`
- Add a tag: `POST /api/tags`
- Update a tag: `PUT /api/tags/:id`
- Delete a tag: `DELETE /api/tags/:id`

## Libraries used

- [dotenv](https://www.npmjs.com/package/dotenv)
- [express](https://www.npmjs.com/package/express)
- [mysql2](https://www.npmjs.com/package/mysql2)
- [sequelize](https://www.npmjs.com/package/sequelize)

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
