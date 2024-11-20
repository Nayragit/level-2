# level-2

1. Start HTML document with DOCTYPE declaration and set the language to English.
2. Inside the <head> section:
   - Set the character set to UTF-8 for proper encoding.
   - Set the viewport meta tag to make the design responsive.
   - Include the external CSS stylesheet (style.css).
3. Inside the <body> section:
   - Create a container with a class of "My-shopping-cart":
     - Add a heading `<h1>` to display "Shopping Cart".
   - Create product divs for each product:
     - Each product is inside a div with classes like "image-1", "image-2", or "image-3".
     - Inside each product div:
       - Add an image tag (`<img>`) with a product image URL and an alt text.
       - Add a div with a class of "product-info" to display product details:
         - Include a title (`<h4>`) for the product name.
         - Display the price inside a `<p>` tag with the class "product-price".
         - Add an input element for quantity with a default value of 1.
         - Add an "Add to Cart" button to trigger the addition of the product to the cart.
4. Add the script.js file to include the JavaScript logic for interaction (such as adding products to the cart).
5. End the HTML document.

CSS :-
   
1. Apply general styles for all elements:
   - Set margin, padding to 0, and use box-sizing border-box for all elements.
2. Set the body styles:
   - Apply a font family (Arial or sans-serif).
   - Set a light background color and add padding for spacing around the page.
3. Style the container (My-shopping-cart):
   - Center the title with some margin at the bottom.
4. Style the product card container (img class):
   - Set the width to 30%, add margin, background color, border radius, and shadow for a card-like appearance.
   - Add a hover effect to scale the product card slightly when the user hovers over it.
5. Style the product images inside the cards:
   - Set the width of the image to 100% to make it responsive, and adjust the height automatically.
6. Style the product information section:
   - Add padding and space out the elements like the title, price, and buttons.
7. Style the title and price:
   - Set bold and larger font size for the product title.
   - Set a distinct color for the price and make it more prominent.
8. Style the input (quantity selector) and button:
   - Set a width for the quantity input and style it with padding, borders, and center text alignment.
   - Style the "Add to Cart" button with a background color, padding, font size, and a hover effect to change the color.
9. Add responsive design using media queries:
   - Adjust the width of product cards to 45% for medium-sized screens (up to 768px).
   - Set the product card width to 100% for smaller screens (up to 480px) to ensure they stack vertically.
