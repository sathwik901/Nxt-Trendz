Nxt Trendz - Cart Features

This project is a continuation of the Nxt Trendz application, focusing on implementing essential cart features using React.js concepts.

Features Implemented

Authentication

Unauthenticated users accessing the Cart Route will be redirected to the Login Route.

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

