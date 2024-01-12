# React comfy-sloth-ecommerce App

## Overview

This React-based e-commerce application is designed to provide users with a seamless shopping experience. It features product browsing, shopping cart functionality, product filtering, responsive design, user authentication via Auth0, and state management using React Context and Reducer.

## Tutorial Credit

This project was created as part of a tutorial by [Coding Addict](https://www.youtube.com/codingaddict). The tutorial provides valuable insights and guidance for building React applications.

## Live Demo :
[live_demo](https://react-comfy-sloth-ecommerce-store.netlify.app/)
## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Project Structure](#project-structure)
- [Reducers](#reducers)
- [Actions](#actions)
- [Dependencies](#dependencies)

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/LouaiKhodary13/react-comfy-sloth-ecommerce.git
   ```

2. cd react-comfy-sloth-ecommerce

3. npm install or yarn install

## Usage

npm start or yarn start
Open your browser and navigate to http://localhost:3000.

## Features

Product Listing: Users can browse a variety of products.

Shopping Cart: Users can add products to their cart, remove items, and adjust quantities.

Product Filtering: Products can be filtered based on various criteria, such as category, color, and price range.

Responsive Design: The application is designed to be responsive and work on different devices.

User Authentication: Auth0 is integrated for user authentication, allowing users to sign in and access personalized features.

State Management: React Context and Reducer are used for efficient state management.

## Project Structure

The project is organized into several key components, including components, pages, reducers, actions, context, utils, and auth0. These components handle UI, state management, and user authentication.

## Reducers

Cart Reducer (cart_reducer)
Handles actions related to the shopping cart, such as adding items, removing items, toggling item amounts, and clearing the entire cart.

Filter Reducer (filter_reducer)
Manages state related to product filtering, including setting the view (grid or list), updating sorting options, filtering products based on various criteria, and clearing applied filters.

Products Reducer (products_reducer)
Manages state related to products, including opening and closing the sidebar, loading products, handling success and error states during product retrieval, and loading single product details.

## Actions

Defines constants for various action types used in the application.

## Dependencies

React: JavaScript library for building user interfaces.
React Router: Provides navigation functionality for single-page applications.
Axios: Promise-based HTTP client for making API requests.
Auth0 React: Library for integrating Auth0 authentication with React applications.
