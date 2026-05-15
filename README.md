# Ex02 Commercial Website
## Date: 10-05-2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM

## welcome.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Stella Sip Station</title>

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600;800&display=swap" rel="stylesheet">

    <style>
        body {
            margin: 0;
            font-family: 'Orbitron', sans-serif;
            background: linear-gradient(to right, #2c003e, #6a0572);
            color: white;
            text-align: center;
        }

        header {
            padding: 40px;
        }

        header h1 {
            font-size: 45px;
            letter-spacing: 3px;
        }

        header p {
            font-size: 18px;
            opacity: 0.9;
        }

        .hero {
            background-image: url("https://images.unsplash.com/photo-1462331940025-496dfbfc7564");
            background-size: cover;
            background-position: center;
            padding: 150px 20px;
        }

        .hero h2 {
            font-size: 55px;
            font-weight: 800;
            text-transform: uppercase;
            letter-spacing: 4px;
            background: linear-gradient(90deg, #ffffff, #ff4da6, #00e5ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 0 15px rgba(255,255,255,0.6),
                         0 0 30px rgba(255,0,255,0.4),
                         0 0 40px rgba(0,255,255,0.4);
        }

        footer {
            padding: 20px;
            background: #1a001f;
            font-size: 14px;
        }
    </style>
</head>

<body>

<header>
    <h1>✨ Stella Sip Station ✨</h1>
    <p>Cosmic. Dreamy. Delicious.</p>
</header>

<section class="hero">
    <h2>Explore the Universe of Flavors</h2>
</section>

<footer>
    © 2026 Stella Sip Station | Designed with 💜 by Natchathira
</footer>

</body>
</html>
```

## menu.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Stella Sip Station</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body{
            margin:0;
            font-family: 'Poppins', sans-serif;
            background-color:#f4f4f4;
        }

        /* Top Section */
        .top-header{
            text-align:center;
            padding:20px;
            background:linear-gradient(to right,#1c1c3c,#3a1c71,#d76d77);
            color:white;
        }

        /* Hero Section */
        .hero{
            height:400px;
            background:url('https://images.unsplash.com/photo-1462331940025-496dfbfc7564');
            background-size:cover;
            background-position:center;
            display:flex;
            align-items:center;
            justify-content:center;
            flex-direction:column;
            color:white;
            text-align:center;
        }

        .hero h1{
            font-size:55px;
            letter-spacing:4px;
            background:rgba(0,0,0,0.6);
            padding:10px 20px;
        }

        .hero p{
            margin-top:10px;
            font-size:18px;
        }

        /* Section Title */
        .section-title{
            text-align:center;
            margin:40px 0 20px;
            font-size:24px;
            font-weight:bold;
        }

        /* Product Grid */
        .products{
            display:flex;
            justify-content:center;
            gap:25px;
            padding:20px;
            flex-wrap:wrap;
        }

        .card{
            width:260px;
            background:white;
            border-radius:12px;
            overflow:hidden;
            box-shadow:0 5px 15px rgba(0,0,0,0.1);
            text-align:center;
            transition:0.3s;
        }

        .card:hover{
            transform:translateY(-8px);
        }

        .card img{
            width:100%;
            height:200px;
            object-fit:cover;
        }

        .card h4{
            margin:12px 0 5px;
        }

        .card p{
            font-size:14px;
            color:gray;
            padding:0 10px;
        }

        .price{
            font-weight:bold;
            margin:10px 0 15px;
        }

        @media(max-width:768px){
            .hero h1{
                font-size:32px;
            }
        }

    </style>
</head>

<body>

    <!-- Welcome Section -->
    <div class="top-header">
        <h2>Welcome to Stella Sip Station</h2>
        <p>Cosmic. Dreamy. Delicious.</p>
    </div>

    <!-- Hero Banner -->
    <div class="hero">
        <h1>NEW COSMIC MENU</h1>
        <p>Explore the Universe of Flavors</p>
    </div>

    <!-- Product Section -->
    <div class="section-title">MOST LOVED</div>

    <div class="products">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93">
            <h4>Moon Latte</h4>
            <p>Creamy latte with cosmic shimmer</p>
            <div class="price">Rs.199</div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1551024601-bec78aea704b">
            <h4>Saturn Donut</h4>
            <p>Ring-shaped galaxy donut</p>
            <div class="price">Rs.149</div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1587248720327-8eb72564be1e">
            <h4>Galaxy Cupcake</h4>
            <p>Colorful cosmic frosting swirl</p>
            <div class="price">Rs.129</div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1499636136210-6f4ee915583e">
            <h4>Nebula Cold Brew</h4>
            <p>Layered purple-blue iced drink</p>
            <div class="price">Rs.179</div>
        </div>

    </div>

</body>
</html>
```

## visit.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Thank You - Stella Sip Station</title>
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            text-align: center;
            color: white;
        }

        header {
            background: linear-gradient(to right, #3a0ca3, #f72585);
            padding: 25px;
            font-size: 20px;
            font-weight: bold;
        }

        .hero {
            background-image: url("https://images.unsplash.com/photo-1462331940025-496dfbfc7564");
            background-size: cover;
            background-position: center;
            padding: 150px 20px;
            position: relative;
        }

        /* Dark overlay like your screenshot */
        .hero::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.6);
        }

        .content {
            position: relative;
            z-index: 1;
        }

        h1 {
            font-size: 50px;
            margin-bottom: 15px;
        }

        p {
            font-size: 20px;
            opacity: 0.9;
        }

        .btn {
            display: inline-block;
            margin-top: 30px;
            padding: 12px 30px;
            background: #f72585;
            color: white;
            text-decoration: none;
            border-radius: 25px;
            transition: 0.3s;
        }

        .btn:hover {
            background: #ff4da6;
            transform: scale(1.05);
        }

        footer {
            background: #1a001f;
            padding: 15px;
            font-size: 14px;
        }
    </style>
</head>

<body>

<header>
    ✨ Stella Sip Station ✨
</header>

<section class="hero">
    <div class="content">
        <h1>💜 Thank You for Visiting!</h1>
        <p>Your journey through the cosmos of flavors means the world to us ✨</p>
        <p>We can't wait to serve you again!</p>

        <a href="index.html" class="btn">Back to Home</a>
    </div>
</section>

<footer>
    © 2026 Stella Sip Station | See You Again 🌟
</footer>

</body>
</html>
```

## OUTPUT

<img width="1917" height="1090" alt="image" src="https://github.com/user-attachments/assets/5d81ff03-f19d-4102-b2e4-33e045e96f50" />

<img width="1919" height="1088" alt="image" src="https://github.com/user-attachments/assets/6e594928-5efe-4cae-b668-22fba8d842d8" />

<img width="1919" height="1088" alt="image" src="https://github.com/user-attachments/assets/fddd6712-7b98-4708-a9bf-f3d8f5ff31ba" />





## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
