<!--
Preview locally: open `index.html` or run `python3 -m http.server 8000 --directory .` then open http://localhost:8000/index.html
Developer note: `index.html` is canonical; README contains a sample copy of the page markup.
-->


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample HTML Document</title>
</head>
    <title>Johns Tee's</title>
<style>
    body {
        margin: 0;
        font-family: cursive;
        line-height: 1.6;
        background-color: gray;
    }
    nav {
        background-color: darkblue;
        color: white;
        padding: 10px 20px;
        justify-content: space-between;
        text-align: center;
    }
    nav .logo {
        font-size: 1.2rem;
        font-weight: bold;
    }
    nav ul {
        list-style: none;
        padding: 0;
        margin: 0;
        display: flex;
        gap: 20px;
    }
    nav ul li a {
        color: white;
        text-decoration: none;
    }
    nav ul li a:hover {
        text-decoration: underline;
    }
    header {
        background: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTyaOC1kq4elrLi6uI-VwNHSs-0u6aYwupGsQ&s') no-repeat center center/cover;
        height: 330px;
        color: black;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
        padding: 120px 20px;
    }
    header h1 {
        font-size: 3rem;
        margin-bottom: 10px;
    }
    header p {
        font-size: 1.5rem;
    }
    main {
        padding: 0 20px;
        margin:  40px auto;
        max-width: 900px;
    }
    .card {
        background: #4607f2ff;
        border-radius: 18px;
        box-shadow: 0 2px 5px rgba(108, 8, 8, 1);
        margin-bottom: 20px;
        overflow: hidden;
        font-size: 14px;
        color: white;
    }
    .btn {
        display:inline-block;
        padding:8px 14px;
        background:darkblue;
        color:white;
        text-decoration:none;
        border-radius:6px;
        font-weight:600;
    }
    h2 {
        margin-top: 0;
    }
    footer {
        background-color: #050000ff;
        color: white;
        text-align: center;
        padding: 10px 20px;
        position: relative;
        bottom: 0;
        width: 100%;
        margin-top: 40px;
    }
    @media (max-width: 600px) {
        nav ul {
            flex-direction: column;
            gap: 10px;
            display: flex; /* keep menu available on small screens */
        }
        header h1 {
            font-size: 2rem;
        }
    }
</style>
</head>
<body>
    <nav>
        <div class="logo">Johns Tee's</div>
        <ul>
            <li><a href="https://github.com/jrmireles5562-blip/proj-2/blob/main/index.html">home</a></li>
            <li><a href="#about">Us</a></li>
            <li><a href="https://j-d-ign.myshopify.com/">custom</a></li>
            <li><a href="./index.html#contact">contact</a></li>
        </ul>
    </nav>
    <header role="img" aria-hidden="true">
        <h1>Welcome to Johns Tee's</h1>
        <p>Your one-stop shop for custom t-shirts</p>
    </header>
    <main>
        <section class="card">
            <h2 id="home">Dyed T-Shirts</h2>
            <p>Explore our range of vibrant dyed t-shirts available in various colors and styles.</p>
            <a class="btn" href="#home">Shop</a>
        </section>
        <section class="card">
            <h2 id="about">Printed T-Shirts</h2>
            <p>Discover our collection of printed t-shirts featuring unique designs and graphics. press home to get started!</p>
        </section>
        <section class="card">
            <h2 id="services">Custom T-Shirts</h2>
            <p>Create your own custom t-shirts with our easy-to-use design tools.</p>
        </section>
        <section class="card">
            <h2 id="contact">Contact Us</h2>
            <p>Get in touch with us for any inquiries or custom orders of our T-Shirts at: 6154873195 or email at Wowhow43@gmail.com </p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Johns Tee's. All rights reserved.</p>
    </footer>
</body>
</html>   