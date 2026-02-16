<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Luxury Fragrance Collection</title>

<style>
body {
    margin: 0;
    background-color: #000;
    color: #fff;
    font-family: Arial, sans-serif;
}

.banner {
    height: 65vh;
    background: url("SPIDER_THEME.png") center/contain no-repeat;
    background-color: #000;
}

.section {
    padding: 80px 20px;
    text-align: center;
}

.section h2 {
    font-size: 2.5rem;
    margin-bottom: 60px;
    color: #fff;
}

.products {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 60px;
}

.product-card {
    background-color: #000;
    padding: 40px;
    border-radius: 15px;
    text-align: center;
}

.product-card img {
    width: 260px;
    background-color: #000;
    padding: 25px;
    border-radius: 12px;
    box-shadow: 0 0 60px #ffffff;
    transition: 0.3s ease;
}

.product-card img:hover {
    box-shadow: 0 0 90px #ffffff;
    transform: scale(1.05);
}

.product-card h3 {
    margin-top: 25px;
    font-size: 1.3rem;
    color: #fff;
}
</style>
</head>

<body>

<div class="banner"></div>

<section class="section">
    <h2>Featured Fragrances</h2>

    <div class="products">

        <div class="product-card">
            <img src="BACCARAT.png" alt="Baccarat Rouge 540">
            <h3>Baccarat Rouge 540</h3>
        </div>

        <div class="product-card">
            <img src="VALENTINO.png" alt="Valentino Born In Roma">
            <h3>Valentino Born In Roma</h3>
        </div>

        <div class="product-card">
            <img src="YSL.png" alt="YSL Eau De Parfum">
            <h3>YSL Eau De Parfum</h3>
        </div>

        <div class="product-card">
            <img src="DIOR.png" alt="Dior Sauvage Eau De Parfum">
            <h3>Dior Sauvage Eau De Parfum</h3>
        </div>

    </div>
</section>

</body>
</html>
