Nxt Trendz - E-commerce Application

This project is a comprehensive e-commerce application named Nxt Trendz built using React.js with various features including authentication, product display, cart management, and navigation.

Features Implemented

Authentication

Users must log in using valid credentials to access the platform.

Unauthenticated users are redirected to the Login Route when trying to access restricted routes like Cart.

Product Listing and Details

Displays a list of products with sorting and filtering options.

Clicking on a product shows detailed information about the product including description, price, and image.

Cart Functionalities

Add to Cart Logic:

Adding the same product multiple times updates the quantity in the cart while keeping the cart item count unchanged.

Cart Summary:

Displays the total amount and number of items in the cart.

Cart Item Management:

Increment: Clicking the plus icon increases the product quantity by one.

Decrement: Clicking the minus icon decreases the product quantity by one.

Remove Item: Clicking the minus icon when quantity is one removes the item from the cart.

The product price and cart summary will update dynamically based on quantity.

Remove All Items:

Clicking the Remove All button clears the entire cart, displaying an Empty Cart View.

Routing

Implemented navigation using React Router DOM for seamless routing between:

Login Page

Home Page

Products Page

Product Details Page

Cart Page

Context API Methods

The CartContext provides the following methods:

cartList - Holds the list of items in the cart.

removeAllCartItems() - Removes all items from the cart.

addCartItem(product) - Adds a product to the cart.

removeCartItem(productId) - Removes a specific product from the cart.

incrementCartItemQuantity(productId) - Increases the quantity of a product in the cart.

decrementCartItemQuantity(productId) - Decreases the quantity of a product in the cart.

Component Structure

src/App.js

src/components/Login

src/components/Home

src/components/Products

src/components/ProductDetails

src/components/Cart

src/components/CartItem

src/components/CartSummary

Icons & Elements

Plus Icon: BsPlusSquare (data-testid="plus")

Minus Icon: BsDashSquare (data-testid="minus")

Remove Icon: AiFillCloseCircle (data-testid="remove")

Product image alt attribute should match the product title.

Prime User Credentials

Username: rahul

Password: rahul@2021

Non-Prime User Credentials

Username: raja

Password: raja@2021

Design & Styling

Primary Colors:

#0b69ff (Blue)

#171f46 (Dark Blue)

#616e7c (Gray)

#ffffff (White)

Font Family: Roboto
