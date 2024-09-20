# online-store
# E-Commerce React Project

## Project Overview

This project is an e-commerce application built using React, Redux Toolkit, and Vite. It showcases a product listing page and a cart page with lazy loading for improved performance. The Redux Toolkit is used to manage the state of the cart items, including total quantity and total price, and this state is accessible to all components.

## Getting Started

To get a local copy of this project up and running, follow these steps:

### Prerequisites

- Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/mohammedqamber/online-store.git
   
2. **Navigate to the project directory:**  

    ```bash
    cd your-repo-name
    
3. **Install the dependencies:**  

    ```bash
    npm install
    
4. **Start the development server:**  

    ```bash
    npm run dev

## Features

## Lazy Loading

Lazy loading is implemented for the product lists page and cart page. This technique helps to improve performance by loading components or parts of the application only when they are needed, reducing the initial load time.

### Benefits of Lazy Loading:
- Improved Performance: By splitting the code and loading only the necessary components, the initial load time is reduced, which enhances the user experience.
- Reduced Bandwidth Usage: It helps in saving bandwidth as only the required components are loaded.
- Better User Experience: Users don't have to wait for the entire application to load before interacting with the visible parts.
  
## State Management with Redux Toolkit

Redux Toolkit is used to manage the state of the shopping cart. The state includes:

- Cart Items: A list of all products added to the cart.
- Total Quantity: The total number of items in the cart.
- Total Price: The total price of the items in the cart.

### Benefits of Using Redux Toolkit:
- Centralized State: All the data related to the cart is managed in a centralized store, making it easier to maintain and debug.
- Global Accessibility: The cart state is accessible to all components, which means you can update or display the cart data from anywhere in your application.
- Efficiency: Using Redux Toolkit's createSlice reduces boilerplate code, making state management more efficient and simpler.    
