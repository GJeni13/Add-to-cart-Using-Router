This task focuses on developing a ReactJS application that incorporates a product listing page and a fully functional cart system, using React Router for navigation and Tailwind CSS for responsive design. Here’s a breakdown of the key steps and functionality:

1. Fetching Products (Product Page)
        API Integration: Use the Fake Store API to fetch a list of products.
Product Display: Show essential details like the product image, title, price, and description.
Responsive Design: Use Tailwind CSS to ensure the layout adapts to different screen sizes, making the product grid user-friendly across all devices.
2. Cart Functionality
        Add to Cart: When a user clicks the "Add to Cart" button on a product, the product should be added to the cart.
Remove from Cart: If the product is already in the cart, the button should change to "Remove from Cart." When clicked, the item should be removed from the cart.
3. Cart Page
Cart Display: List all items added to the cart. Each cart item shows:
  * Product name
  * Price
  * Quantity
A "Remove from Cart" button
      Quantity Adjustment: Users can increase or decrease the quantity of each item. The total price for each item should be updated based on the quantity.
      Dynamic Total Calculation: The cart page displays the dynamically updated total price, which reflects the sum of the item prices (based on their quantity).
      A 10% discount should be applied to the final total price.
4. State Management
      State Updates: Ensure that when a product is added or removed from the cart, the application's state is updated appropriately. This includes adjusting the total price and reflecting changes in both the product and cart pages.
5. Routing with React Router
    Navigation: Use React Router to create separate routes for the Product Page and Cart Page.
        A Product Page that lists all products.
      A Cart Page that shows the items in the cart and allows users to modify the cart.
6. Styling with Tailwind CSS
    Consistent Styling: Use Tailwind CSS for uniform styling across the app. It will ensure a clean and responsive layout, particularly for the product grid, buttons, and cart interface.
Key Features Summary:
  * Product fetching and display (with API)
  * Cart system: Add, remove, and adjust quantity
  * Cart total and 10% discount calculations
  * Navigation between pages using React Router
  * Responsive design with Tailwind CSS









