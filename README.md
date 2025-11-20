<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thrift - Mens Clothing</title>

    <style>
        body {
            margin: 0;
            background: #111;
            color: #fff;
            font-family: 'Arial', sans-serif;
        }

        /* Header */
        header {
            background: #000;
            padding: 25px;
            text-align: center;
            font-size: 32px;
            font-weight: bold;
            letter-spacing: 3px;
            border-bottom: 2px solid #444;
        }

        /* Banner */
        .banner {
            background: url('https://images.unsplash.com/photo-1521572163474-6864f9cf17ab') no-repeat center/cover;
            height: 320px;
            border-bottom: 2px solid #333;
        }

        /* Section */
        .section {
            padding: 25px;
            text-align: center;
        }
        .section h2 {
            font-size: 28px;
            margin-bottom: 10px;
            color: #f4f4f4;
        }

        /* Product Grid */
        .products {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        .item {
            background: #1b1b1b;
            width: 210px;
            padding: 12px;
            border-radius: 12px;
            box-shadow: 0 0 15px #000;
            border: 1px solid #333;
            transition: 0.3s;
        }

        .item:hover {
            transform: scale(1.05);
            box-shadow: 0 0 25px #444;
        }

        .item img {
            width: 100%;
            border-radius: 10px;
        }

        .item p {
            font-size: 18px;
            margin: 10px 0 5px;
            font-weight: bold;
        }

        .price {
            color: #0f0;
            font-size: 17px;
            margin-bottom: 10px;
        }

        /* Buttons */
        .btn {
            background: #fff;
            color: #000;
            padding: 10px 15px;
            text-decoration: none;
            display: inline-block;
            border-radius: 6px;
            font-weight: bold;
            margin-top: 8px;
        }

        .btn:hover {
            background: #ddd;
        }

        /* Payment Button */
        .pay-btn {
            background: #0f0;
            color: #000;
            padding: 12px 20px;
            font-size: 18px;
            border-radius: 8px;
            text-decoration: none;
            display: inline-block;
            margin-top: 20px;
            font-weight: bold;
        }

        /* Footer */
        footer {
            background: #000;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
            border-top: 2px solid #333;
            font-size: 14px;
        }
    </style>
</head>

<body>

<header>THRIFT – MENS CLOTHING</header>

<div class="banner"></div>

<div class="section">
    <h2>Our Mens Collection</h2>
    <p>Premium thrift menswear at best & affordable prices.</p>

    <div class="products">

        <div class="item">
            <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab">
            <p>Casual Shirt</p>
            <div class="price">₹499</div>
            <a class="btn" href="https://wa.me/91XXXXXXXXXX">WhatsApp Order</a>
        </div>

        <div class="item">
            <img src="https://images.unsplash.com/photo-1512436991641-6745cdb1723f">
            <p>Blue Jeans</p>
            <div class="price">₹699</div>
            <a class="btn" href="https://wa.me/91XXXXXXXXXX">WhatsApp Order</a>
        </div>

        <div class="item">
            <img src="https://images.unsplash.com/photo-1503341455253-b2e723bb3dbb">
            <p>Oversized T-Shirt</p>
            <div class="price">₹399</div>
            <a class="btn" href="https://wa.me/91XXXXXXXXXX">WhatsApp Order</a>
        </div>

    </div>

    <br><br>

    <!-- PAYMENT BUTTON WITH UPI -->
    <a class="pay-btn" href="upi://pay?pa=ajithkumar94099-2@okaxis&pn=ThriftClothing&cu=INR">
        Pay Now (UPI)
    </a>

</div>

<footer>
    © 2025 Thrift Mens Clothing | All Rights Reserved
</footer>

</body>
</html>
