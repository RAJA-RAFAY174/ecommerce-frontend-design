Brand Ecommerce Website
=======================

Overview
--------
This project is a modern, responsive e-commerce website redesign. It features a completely overhauled UI based on a provided mockup, including a dynamic home page, a functional shop with category filtering, detailed product pages, a shopping cart with local storage persistence, and a simulated checkout process with order history tracking.

Features
--------
1.  **Home Page (`index.html`)**:
    *   Responsive hero section with sidebar navigation.
    *   "Deals and Offers" section with a countdown timer.
    *   Category-specific sections for "Home and Outdoor" and "Consumer Electronics".
    *   Recommended items grid.
    *   Newsletter subscription form.

2.  **Shop Page (`shop.html`)**:
    *   Sidebar filters for Categories, Brands, Features, Price Range, Condition, and Ratings.
    *   Dynamic product grid that filters based on URL parameters (e.g., `?category=tech`).
    *   List/Grid view toggles (visual only).

3.  **Product Page (`product.html`)**:
    *   Detailed product view with an image gallery.
    *   Product information, stock status, and pricing tiers.
    *   "Add to Cart" functionality.
    *   Related products section.

4.  **Shopping Cart (`cart.html`)**:
    *   Lists added items with quantity adjustment and removal options.
    *   Dynamic subtotal, tax, and total calculation.
    *   Coupon input field (visual only).
    *   "Checkout" button that processes the order.

5.  **Order History (`orders.html`)**:
    *   Displays a list of past orders.
    *   Shows order status, total amount, and items purchased.
    *   Data is persisted using the browser's `localStorage`.

6.  **Global Features**:
    *   **Responsive Design**: Works on desktop, tablet, and mobile.
    *   **Navigation**: Functional links across all pages.
    *   **State Management**: Cart and Order data are saved in `localStorage`, so they persist across page reloads.

Technologies Used
-----------------
*   **HTML5**: Semantic structure.
*   **CSS3**: Custom styling with CSS variables for theming, Flexbox, and Grid for layout.
*   **JavaScript (Vanilla)**: DOM manipulation, event handling, URL parameter parsing, and `localStorage` management.
*   **Font Awesome**: Icons for UI elements.
*   **Inter Font**: Google Font for typography.

How to Run
----------
1.  **Download/Clone** the project folder.
2.  **Open** the `index.html` file in any modern web browser (Chrome, Firefox, Edge, etc.).
3.  **Navigate** through the site using the links and buttons.
    *   Click "Shop" or sidebar categories to browse products.
    *   Click on a product to view details.
    *   Click "Add to cart" to add items.
    *   Go to "My Cart" to view and manage items.
    *   Click "Checkout" to place an order.
    *   View your "Orders" to see past purchases.

File Structure
--------------
*   `index.html`: Main landing page.
*   `shop.html`: Product listing and filtering page.
*   `product.html`: Individual product detail page.
*   `cart.html`: Shopping cart page.
*   `orders.html`: User order history page.
*   `style.css`: Global stylesheet containing all CSS variables and styles.
*   `script.js`: Core logic for product rendering, cart management, and order processing.
*   `data.js`: Mock data file containing product information.
*   `assets/`: Folder containing images and icons.

Use of AI
---------
This project was developed with the assistance of an AI coding assistant. The AI helped in:
*   **Code Generation**: Writing HTML structure, CSS styling, and JavaScript logic.
*   **Debugging**: Identifying and fixing issues with category filtering and cart functionality.
*   **Content Creation**: Generating placeholder product data and documentation.
*   **Design Implementation**: Translating high-level design descriptions into functional code.

Notes
-----
*   **Data Persistence**: Since this project uses `localStorage`, clearing your browser cache/data will remove your cart and order history.
*   **Images**: Ensure the `assets` folder is in the same directory as the HTML files for images to load correctly.
