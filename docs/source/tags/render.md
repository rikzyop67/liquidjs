<div class="product-container">
  <!-- Your product information goes here -->

  <div class="add-to-cart-container">
    <button id="add-to-cart-btn">Add to Cart</button>
  </div>
</div>

<!-- CSS (you can include this in your theme's style file) -->
<style>
  .add-to-cart-container {
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
    background-color: #fff; /* Adjust the background color as needed */
    box-shadow: 0px -2px 5px 0px rgba(0, 0, 0, 0.1); /* Optional: Add a subtle shadow */
    z-index: 999; /* Make sure the button is above other elements */
    text-align: center;
  }

  #add-to-cart-btn {
    padding: 10px 20px;
    font-size: 16px;
    background-color: #007bff; /* Adjust the button color as needed */
    color: #fff; /* Adjust the text color as needed */
    border: none;
    cursor: pointer;
  }
</style>

<!-- JavaScript (you can include this in your theme's script file) -->
<script>
  document.addEventListener('DOMContentLoaded', function () {
    var addToCartBtn = document.getElementById('add-to-cart-btn');
    
    addToCartBtn.addEventListener('click', function () {
      // Add your logic here to handle the 'Add to Cart' functionality
      // For example, you can use Shopify's AJAX API to add the product to the cart.
      // The specific implementation will depend on your Shopify setup and requirements.
    });
  });
</script>
