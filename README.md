# E-commerce-product-page
E-commerce product page provide essential information about products, helping customers understand if it meet the product needs
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<div class="container">
    <div class="product">
        <img src="product-image.jpg" alt="Product Image">
        <h2 class="product-name">Product Name</h2>
        <p class="product-price">$XX.XX</p>
        <p class="product-description">Product description lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <button class="btn-add-to-cart">Add to Cart</button>
    </div>
</div>

</body>
</html>
CSS
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

.product {
    border: 1px solid #ccc;
    padding: 20px;
    text-align: center;
}

.product img {
    max-width: 100%;
    height: auto;
    margin-bottom: 10px;
}

.product-name {
    font-size: 24px;
    margin-bottom: 10px;
}

.product-price {
    font-size: 18px;
    font-weight: bold;
    color: #333;
    margin-bottom: 10px;
}

.product-description {
    margin-bottom: 20px;
}

.btn-add-to-cart {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    font-size: 16px;
    border: none;
    cursor: pointer;
    border-radius: 4px;
}

.btn-add-to-cart:hover {
    background-color: #45a049;
}
