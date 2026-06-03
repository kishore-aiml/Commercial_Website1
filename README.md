# Ex02 Commercial Website
## Date:03/06/2026

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
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TechNova Store</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Arial,sans-serif}
body{background:#f4f4f4}
header{background:#222;color:white;padding:15px 40px;display:flex;justify-content:space-between;align-items:center}
nav a{color:white;text-decoration:none;margin-left:20px}
.hero{background:linear-gradient(135deg,#4a90e2,#6a11cb);color:white;text-align:center;padding:80px 20px}
.hero h1{font-size:48px}
.hero p{margin:15px 0}
.btn{display:inline-block;background:white;color:#333;padding:12px 25px;border-radius:5px;text-decoration:none}
.products{padding:50px 20px}
.products h2{text-align:center;margin-bottom:30px}
.grid{display:flex;gap:20px;justify-content:center;flex-wrap:wrap}
.card{background:white;width:250px;padding:20px;border-radius:10px;box-shadow:0 2px 8px rgba(0,0,0,.1);text-align:center}
.card img{width:100%;border-radius:8px}
footer{background:#222;color:white;text-align:center;padding:20px;margin-top:40px}
</style>
</head>
<body>
<header>
<h2>TechNova</h2>
<nav>
<a href="#">Home</a>
<a href="#">Products</a>
<a href="#">Services</a>
<a href="#">Contact</a>
</nav>
</header>

<section class="hero">
<h1>Welcome to TechNova Store</h1>
<p>Your One-Stop Destination for Smart Gadgets</p>
<a href="#" class="btn">Shop Now</a>
</section>

<section class="products">
<h2>Featured Products</h2>
<div class="grid">
<div class="card">
<img src="https://via.placeholder.com/250x150" alt="Product">
<h3>Smart Watch</h3>
<p>$99</p>
</div>
<div class="card">
<img src="https://via.placeholder.com/250x150" alt="Product">
<h3>Wireless Earbuds</h3>
<p>$59</p>
</div>
<div class="card">
<img src="https://via.placeholder.com/250x150" alt="Product">
<h3>Gaming Mouse</h3>
<p>$39</p>
</div>
</div>
</section>

<footer>
<p>&copy; 2026 TechNova Store. All Rights Reserved.</p>
</footer>
</body>
</html>
```
## OUTPUT
<img width="1918" height="931" alt="image" src="https://github.com/user-attachments/assets/66c49a15-dc81-4f94-97f0-f526317e883f" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
