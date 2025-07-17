# Shopper E-Commerce Frontend

User-facing web application for the Shopper full-stack e-commerce platform.

## Features

- Browse products by category: Men, Women, Kids
- Product details and images
- Add/remove items to/from cart
- User authentication (Login/Signup)
- View and manage cart
- Responsive design

## Tech Stack

- **Frontend:** React
- **Routing:** React Router
- **State Management:** React Context API
- **Backend API:** [Shopper E-Com Backend](../shopper-e-com-backend)
- **Deployment:** Railway (backend), local or cloud (frontend)

## Getting Started

### Prerequisites

- Node.js (>=14)
- npm

### Installation

```bash
git clone https://github.com/Areeb22297/shopper-e-com-frontend.git
cd shopper-e-com-frontend
npm install
```

### Running the App

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Configuration

- Backend API endpoint is set in `src/App.js`:
  ```
  export const backend_url = 'https://shopper-e-com-backend.up.railway.app';
  ```
- Currency is set to INR (`₹`).

## Folder Structure

- `src/Components`: UI components (Navbar, Footer, etc.)
- `src/Pages`: Main pages (Shop, Cart, Product, LoginSignup, ShopCategory)
- `src/Context`: React Context for global state
- `src/App.js`: Main app and routing
- `src/index.js`: Entry point

## Usage

- Browse products by category
- View product details
- Add products to cart
- Login or signup to persist your cart
- View and manage your cart

## License

MIT

## Acknowledgements

- [Create React App](https://github.com/facebook/create-react-app)
- `src/App.js`: Main app and routing
- `src/index.js`: Entry point

## Usage

- Browse products by selecting categories from the navbar.
- Click on a product to view details.
- Add products to your cart.
- Login or signup to persist your cart.
- View and manage your cart.
- Checkout (UI only).

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](LICENSE)
