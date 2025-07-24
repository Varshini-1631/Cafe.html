<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>The Coffee Lounge!!!!✨</title>

    <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-weight: 100;
      }
      @media only screen and (max-width: 600px) {
        body {
          font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
            "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
          background-color: #be9067;
          color: #61473b;
          animation: fadeIn 1.2s ease-in;
        }
      }
      header {
        background-color: #916b4f;
        color: white;
        padding: 20px;
        text-align: center;
      }
      nav {
        text-align: center;
      }
      nav a:hover {
        color: black;
        text-underline-position: below;
      }

      h1 {
        text-align: center;
      }

      .coffee {
        text-align: center;
        padding: 144px 25px;
        background: url(https://plus.unsplash.com/premium_photo-1675435644687-562e8042b9db?q=80&w=449&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)
          no-repeat left/cover;
        color: white;
        border: #876349;
      }
      footer {
        background-color: #6f4e37;
        color: #fffaf0;
        padding: 2px 0px;
        width: auto;
        font-size: 0.95rem;
        border-top: 4px solid #a78765;
        text-align: center;
      }
      nav.fixed {
        text-align: center;
      }

      .Cup {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
        gap: 20px;
        padding: 20px;
      }

      .Cup > div {
        background-color: #fff5ee;
        padding: 15px;
        border-radius: 12px;
        box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.1);
        width: auto;
        text-align: center;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
      }
      .Cup > div:hover {
        transform: translateY(-5px);
        box-shadow: 4px 4px 20px rgba(174, 117, 117, 0.2);
      }
      .header-bar {
        display: flex;
        align-items: center;
        gap: 20px;
        background-color: #916b4f;
        color: white;
        padding: 20px;
      }
      .logo {
        height: 45px;
        width: auto;
        padding: 0px 10px;
        border-radius: 200px;
      }

      .header-text h1,
      .header-text p {
        margin: 0;
      }
      .menu-image {
        width: 100%;
        height: 150px;
        object-fit: contain;
        border-radius: 8px;
        margin-bottom: 10px;
      }
      @keyframes fadeIn {
        from {
          opacity: 0;
          transform: translateY(5px);
        }
        to {
          opacity: 1;
          transform: translateY(0);
        }
      }

      .text {
        margin-bottom: 10px;
      }
      #contact {
        display: flex;
        flex-direction: column;
        align-items: center;
        background-color: #fffaf0;
        padding: 40px 20px;
        border-top: 3px solid #c49a6c;
        margin-top: 40px;
      }

      #contact h2 {
        color: #6f4e37;
        font-size: 2rem;
        margin-bottom: 20px;
        text-align: center;
      }

      .form-row {
        display: flex;
        flex-direction: column;
        margin-bottom: 20px;
        width: 100%;
        max-width: 400px;
      }

      label {
        font-weight: bold;
        margin-bottom: 8px;
        color: #61473b;
      }

      input {
        padding: 10px;
        border: 1px solid #d3b89f;
        border-radius: 8px;
        font-size: 1rem;
      }

      input:focus {
        outline: none;
        border-color: #916b4f;
        box-shadow: 0 0 5px rgba(145, 107, 79, 0.5);
        background-color: #fff8f4;
      }
      button.submit {
        background-color: #916b4f;
        color: white;
        padding: 12px 24px;
        margin-bottom: 10px;
        border: #916b4f;
        text-align: center;
        border-radius: 12px;
        cursor: pointer;
      }
      nav {
        background: #a6553c;
        padding: 10px;
        text-align: center;
      }
      nav a {
        margin: 0 15px;
        color: white;
        text-decoration: none;
        font-weight: bold;
      }
    </style>
  </head>
  <body>
    <header>
      <section id="home">
        <img
          src="https://tse3.mm.bing.net/th?id=OIP.eHYLNCP8uys-O78G-YChLgHaHa&pid=Api&P=0&h=220"
          alt="The Coffee Lounge Logo"
          class="logo" />
        <h1>The Coffee Lounge!</h1>
        <p>
          Your Daily Dose, Coffee. Community. Cozy, Better Coffee. Better Mood,
          Your Perfect Cup, and Brewed with Love!!!!!🍂🧸🥐☕🍪
        </p>
      </section>
    </header>
    <nav>
      <a href="#home">Home</a>
      <a href="#menu">Menu</a>
      <a href="#contact">Contact</a>
    </nav>
    <section class="coffee">
      <h1>HELLO SUNSHINES!!🌞</h1>
      <h1>Welcome to The Coffee Lounge!!!!✨</h1>
      <p>Rise and grind</p>
    </section>
    <br />
    <section id="menu">
      <h1>MENU☕</h1>
      <section class="Cup">
        <div class="Expresso">
          <img
            src="https://gigericeira.com/wp-content/uploads/2020/04/jeremy-yap-jn-HaGWe4yw-unsplash2-scaled.jpg"
            alt="expresso"
            class="menu-image" />
          <h3>Espresso</h3>
          <p>More espresso less depresso</p>
        </div>
        <div class="Cappuccino">
          <img
            src="https://www.bennett-shop.de/wp-content/uploads/2014/12/cappuccino.jpg"
            alt="cappuccino"
            class="menu-image" />
          <h3>Cappuccino</h3>
          <p>What do you call a sad cappuccino?</p>
        </div>
        <div class="Cold-brew">
          <img
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSa7WsnRwoJDyJq0UPUW9_fW1U04Hduq4w_7w&s"
            alt="Cold-Brew"
            class="menu-image" />
          <h3>Cold-Brew</h3>
          <p>Chilled and smooth for sunny days.</p>
        </div>
        <div class="Hot-chocolate">
          <img
            src="https://lizzylovesfood.com/wp-content/uploads/2021/09/Delysia-Hot-Chocolate-Recipe-9.jpg"
            alt="Hot-chocolate"
            class="menu-image" />
          <h3>Hot Chocolate</h3>
          <p>Sipping on pure happiness.</p>
        </div>
        <div class="Mini-Pancakes">
          <img
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSewqMXfOUhSrh5U_fFU0uOu9l0mqk88r8ZRA&s"
            alt="Mini Pancakes"
            class="menu-image" />
          <h3>Mini Pancakes</h3>
          <p>Rise and shine, it’s pancake time!</p>
        </div>
        <div class="Kid-Friendly-Sandwich">
          <img
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS9uRjMm6h7ZjPJwZrDQmvqDXylb3ML74M4xg&s"
            alt="Kid-Friendly Sandwich"
            class="menu-image" />
          <h3>Kid-Friendly Sandwich</h3>
          <p>A sandwich a day keeps the sadness away.</p>
        </div>
        <div class="Mini-Pizzas">
          <img
            src="https://www.budgetbytes.com/wp-content/uploads/2016/06/Freezer-Ready-Mini-Pizzas-baked-front-1.jpg"
            alt="Mini Pizzas"
            class="menu-image" />
          <h3>Mini Pizzas</h3>
          <p>I think of dieting, then I eat pizza.</p>
        </div>
        <div class="Spiced-Blueberry-Smoothie-Bowl">
          <img
            src="https://hips.hearstapps.com/hmg-prod/images/spiced-blueberry-smoothie-bowl-64b035b1a97ab.jpg?crop=0.668xw:1.00xh;0.128xw,0&resize=2048:*"
            alt="Spiced Blueberry Smoothie Bowl"
            class="menu-image" />
          <h3>Spiced Blueberry Smoothie Bowl</h3>
          <p>Beat the heat.</p>
        </div>
        <div class="Cookies">
          <img
            src="https://www.profitableventure.com/wp-content/uploads/2020/06/Cost-Cookie-Chips.jpg"
            alt="Cookies"
            class="menu-image" />
          <h3>Cookies</h3>
          <p>People's most favorite</p>
        </div>
        <div class="Croissants">
          <img
            src="https://insanelygoodrecipes.com/wp-content/uploads/2024/12/Chocolate-Almond-Croissants-Recipe-500x375.jpg"
            alt="Croissants"
            class="menu-image" />
          <h3>Croissants</h3>
          <p>But first, croissants....</p>
        </div>
        <div class="Crepes">
          <img
            src="https://ourbestbites.com/wp-content/uploads/2010/06/UB5A8290-2.jpg"
            alt="Crepes"
            class="menu-image" />
          <h3>Crepes</h3>
          <p>Spread love, Nutella, and crepes.</p>
        </div>
        <div class="Macarons">
          <img
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRoPDQB9lkguSoh44JTibOhXYSevs5BAQpnsg&s"
            alt="Macarons"
            class="menu-image" />
          <h3>Macarons</h3>
          <p>Macaron magic!</p>
        </div>
        <div class="Cupcakes">
          <img
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRP9GLy7_Lvf8BVkXuG2nyvcBe0DNZc_eYp1g&s"
            alt="Cupcakes"
            class="menu-image" />
          <h3>Cupcakes</h3>
          <p>Just like cupcakes, life is better when it's sweet</p>
        </div>
        <div class="Pasta">
          <img
            src="https://s.lightorangebean.com/media/20240914160809/Spicy-Penne-Pasta_-done.png"
            alt="Pasta"
            class="menu-image" />
          <h3>Pasta</h3>
          <p>Pasta la vista, hunger!</p>
        </div>
        <div class="Stuffed-Shells">
          <img
            src="https://tse4.mm.bing.net/th?id=OIP.bGNZE3b3PePevNzXr2wfiAHaHa&pid=Api&P=0&h=220"
            alt="Stuffed-Shells"
            class="menu-image" />
          <h3>Stuffed Shells</h3>
          <p>Shellsss!!yess please!</p>
        </div>
      </section>
    </section>
    <form>
      <section id="contact">
        <h2>CONTACT US:</h2>
        <br />
        <div class="form-row">
          <label for="name">Full Name:</label>
          <input
            id="name"
            type="text"
            placeholder="Enter your full name"
            required />
        </div>
        <div class="form-row">
          <label for="phone">Phone Number:</label>
          <input
            id="phone"
            type="tel"
            placeholder="+91-9876543210"
            pattern="[0-9]{10}"
            required />
        </div>
        <div class="form-row">
          <label for="email">Email Address:</label>
          <input
            id="email"
            type="email"
            placeholder="you@example.com"
            required />
        </div>
        <button class="submit">SUBMIT</button>
      </section>
    </form>
    <footer>
      <nav>
        Follow us on
        <a href="https://www.instagram.com" target="_blank">Instagram</a>
        <a href="https://www.facebook.com" target="_blank">Facebook</a>
        <a href="https://www.twitter.com" target="_blank">Twitter</a>

        <p>©️ 2025 The Coffee Lounge!!!!✨. All rights reserved.</p>

        For inquiries:
        <a href="mailto:info@coffeelounge.com">info@coffeelounge.com</a>
      </nav>
    </footer>
  </body>
</html>
