# React Food Order App

This is a simple food ordering application built with React. It allows users to browse a list of meals, add them to a cart, and place an order.

## Features

*   Browse a list of available meals.
*   Add and remove items from the shopping cart.
*   View the total amount of the items in the cart.
*   Submit the order.

## Technologies Used

### Frontend

*   React
*   Vite
*   React Context API for state management
*   CSS Modules for styling

### Backend

*   Node.js
*   Express.js

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

*   npm
    ```sh
    npm install npm@latest -g
    ```

### Installation

1.  Clone the repo
    ```sh
    git clone https://github.com/your_username_/Project-Name.git
    ```
2.  Install NPM packages for the frontend
    ```sh
    npm install
    ```
3.  Install NPM packages for the backend
    ```sh
    cd backend
    npm install
    ```

### Running the application

1.  Start the backend server
    ```sh
    cd backend
    npm start
    ```
2.  Start the frontend development server
    ```sh
    npm run dev
    ```

## Project Structure

```
.
├── backend
│   ├── app.js
│   ├── data
│   │   ├── available-meals.json
│   │   └── orders.json
│   └── public
│       └── images
├── public
│   └── logo.jpg
├── src
│   ├── components
│   │   ├── Cart.jsx
│   │   ├── CartItem.jsx
│   │   ├── Checkout.jsx
│   │   ├── Error.jsx
│   │   ├── Header.jsx
│   │   ├── MealItem.jsx
│   │   ├── Meals.jsx
│   │   └── UI
│   │       ├── Button.jsx
│   │       ├── Input.jsx
│   │       └── Modal.jsx
│   ├── hooks
│   │   └── useHttp.js
│   ├── store
│   │   ├── CartContext.jsx
│   │   └── UserProgressContext.jsx
│   └── util
│       ├── constants.js
│       └── formatting.js
├── index.html
├── package.json
└── vite.config.js
```
