<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Digital Sell Service</title>

<style>
body {
    font-family: Arial;
    margin: 0;
    background: #f5f5f5;
}

header {
    background: #1877f2;
    color: white;
    padding: 15px;
    text-align: center;
}

.container {
    padding: 20px;
}

.card {
    background: white;
    padding: 15px;
    margin-bottom: 15px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

button {
    background: #25D366;
    color: white;
    border: none;
    padding: 10px;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background: #1ebe5d;
}
</style>
</head>

<body>

<header>
    <h2>📱 Digital Sell Service</h2>
    <p>Facebook & Instagram Marketing</p>
</header>

<div class="container">

    <div class="card">
        <h3>📘 Facebook Sell Service</h3>
        <p>আপনার পণ্য ফেসবুকে সেল করুন সহজে</p>
        <button onclick="order()">অর্ডার করুন</button>
    </div>

    <div class="card">
        <h3>📸 Instagram Sell Service</h3>
        <p>Instagram এর মাধ্যমে সেল বাড়ান</p>
        <button onclick="order()">অর্ডার করুন</button>
    </div>

    <div class="card">
        <h3>💎 Premium Packages</h3>
        <p>৳400 - Basic</p>
        <p>৳800 - Standard</p>
        <p>৳1200 - Advanced</p>
        <p>৳2000 - Pro</p>
        <button onclick="order()">প্যাকেজ নিন</button>
    </div>

</div>

<script>
function order(){
    window.location.href = "https://wa.me/8801314305569";
}
</script>

</body>
</html>
