# Canaan-Restaurant - A secured RESTful App for Restaurant

## Setup

1. Clone the repository
2. Change directory into frontend: `cd frontend`, run `npm install`, then run `npm start`
3. Open a new tab in your terminal, type `cd backend` then run `cp .env.example .env` to create .env file
4. In that tab, run `docker compose up --build`

## Account to test:

1. Role: OWNER
- owner@example.com
- secret

2. Role: DRIVER
- driver@example.com
- secret

3. Role: USER
- user@example.com
- secret

## Completed Tasks:
- User authentication and authorization
- Management of restaurants and menus
- Order management

## Underdevelopment Tasks:
- Notification system

Import Postman collection from this file:

### /backend/api/pkg/postman/restaurant.postman_collection.json

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.