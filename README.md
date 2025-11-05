# Express.js REST API

## Setup Instructions
1. Clone repository
2. Run `npm install`
3. Create `.env` from `.env.example`
4. Start server with: `node server.js`

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET    | /api/products | List products (with pagination, filtering, search) |
| GET    | /api/products/:id | Get product by ID |
| POST   | /api/products | Create product (Auth required) |
| PUT    | /api/products/:id | Update product |
| DELETE | /api/products/:id | Delete product |
| GET | /api/products/stats/count | Product count by category |

### Auth Requirement
Add API key in request headers:
# new
