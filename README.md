Fixes and Improvements

Backend ("server.js")

- Line 23: Prevented duplicate registrations by checking if the user already exists before allowing registration.
- Line 35: Simplified response logic using "res.json({ success: !!user })".
- Line 40: Added password verification during authentication.
- Line 48: Replaced "Date.now()" with "productID" for better identifier handling.
- Line 59: Updated logic to correctly push "orderID" into the orders list.

Frontend ("app.js")

- Line 40: Added error handling to throw an error when a fetch request fails.
- Line 62: Ensured "cartItems" are properly pushed into the cart.

Styling ("style.css")

- Line 38: Removed left alignment to improve layout consistency.
- Line 45: Updated button text color for better visibility.
- Line 62: Changed center box text color for improved readability.

General Fixes

- Masked password input fields for security.
- Fixed broken links caused by incorrect file extensions.
