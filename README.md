<html>
<head>
    <title>ShopOrder</title>
    <style>
        /* Add some basic styling for the app */
        body { background-color: #f5f5f5; font-family: Arial, sans-serif; }
        .container { text-align: center; margin-top: 50px; }
        .item { padding: 10px; border: 1px solid #ccc; margin: 10px; display: inline-block; cursor: pointer; }
    </style>
</head>
<body>
    <div class="container">
        <h1>ShopOrder</h1>
        <div class="item" onclick="orderItem('kalu')">Milk</div>
        <div class="item" onclick="orderItem('Stove')">Stove</div>
        <div class="item" onclick="orderItem('Smoking Object')">Smoking Object</div>
    </div>
    <script>
        function orderItem(itemName) {
            const phoneNumber = '9989425295';
            const quantity = 1; // Hardcoded for now
            alert(`Ordering ${itemName}`);

            // Example to send SMS (you will need an API)
            // Use a service like Twilio to send the SMS
        }
    </script>
</body>
</html>
