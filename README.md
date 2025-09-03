<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Zubair's Boutique</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <img src="images/logo.png" alt="Zubair's Boutique Logo" class="logo">
    <h1>Zubair's Boutique</h1>
    <p class="slogan">Elegance stitched in every thread</p>
  </header>

  <section class="hero">
    <h2>Welcome to Zubair's Boutique</h2>
  </section>

  <section class="about">
    <h2>About Us</h2>
    <p>At Zubair’s Boutique, we believe that true elegance lies in the details. 
    Our collection of ready-made and unstitched ladies’ garments is crafted with care, 
    blending modern trends with timeless tradition. From everyday wear to occasion outfits, 
    we bring you quality fabrics, graceful designs, and a touch of sophistication stitched in every thread.</p>
  </section>

  <section class="products">
    <h2>Our Collection</h2>
    <div class="product-grid">
      <div class="product">
        <img src="images/product1.jpg" alt="3-Piece Cotton Set">
        <h3>3-Piece Cotton Set</h3>
        <p>₹1500</p>
        <a href="https://wa.me/917506487605?text=I%20want%20to%20order%20the%203-Piece%20Cotton%20Set" class="btn">Shop Now</a>
      </div>
      <div class="product">
        <img src="images/product2.jpg" alt="3-Piece Cotton Set">
        <h3>3-Piece Cotton Set</h3>
        <p>₹1500</p>
        <a href="https://wa.me/917506487605?text=I%20want%20to%20order%20the%203-Piece%20Cotton%20Set" class="btn">Shop Now</a>
      </div>
      <div class="product">
        <img src="images/product3.jpg" alt="3-Piece Cotton Set">
        <h3>3-Piece Cotton Set</h3>
        <p>₹1500</p>
        <a href="https://wa.me/917506487605?text=I%20want%20to%20order%20the%203-Piece%20Cotton%20Set" class="btn">Shop Now</a>
      </div>
    </div>
  </section>

  <section class="contact">
    <h2>Contact Us</h2>
    <p>Phone: +91 7506487605</p>
    <a href="https://wa.me/917506487605" class="btn">Chat on WhatsApp</a>
    <form name="contact" method="POST" data-netlify="true" action="thankyou.html">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" placeholder="Your Message" required></textarea>
      <button type="submit" class="btn">Send</button>
    </form>
  </section>

  <footer>
    <p>📞 +91 7506487605</p>
    <p>Made with ❤️ by Zubair's Boutique</p>
  </footer>

  <a href="https://wa.me/917506487605" class="whatsapp-float">💬</a>
</body>
</html>
