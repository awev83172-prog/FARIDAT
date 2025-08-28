<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SHOP W FAFA | Home</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    body { font-family: "Poppins", sans-serif; }
    h1,h2,h3,h4 { font-family: "Playfair Display", serif; }
    .shadow-fade { box-shadow: 0 8px 30px rgba(0,0,0,0.3); }
    .hover-scale { transition: transform 0.35s ease; }
    .hover-scale:hover { transform: scale(1.05); }
    .fade-up { opacity:0; transform: translateY(25px); transition: all 0.9s ease; }
    .fade-up.show { opacity:1; transform: translateY(0); }
    .discount { color: #D946EF; font-weight: 600; }
  </style>
</head>
<body class="bg-gradient-to-b from-pink-50 via-white to-purple-50 text-gray-900">

  <!-- NAVBAR -->
  <header class="bg-white/90 backdrop-blur sticky top-0 z-50 shadow-sm">
    <div class="max-w-7xl mx-auto flex items-center justify-between p-4">
      <div class="flex items-center gap-3">
        <img src="logo.jpg" alt="SHOP W FAFA Logo" class="w-14 h-14 rounded-full shadow-fade hover-scale">
        <a href="index.html" class="text-2xl font-bold text-purple-600 hover:text-purple-700 transition">SHOP W FAFA</a>
      </div>
      <nav class="hidden md:flex gap-6 text-gray-700 font-medium">
        <a href="index.html" class="hover:text-purple-600 transition font-semibold">Home</a>
        <a href="about.html" class="hover:text-purple-600 transition">About</a>
        <a href="shop.html" class="hover:text-purple-600 transition">Shop</a>
        <a href="contact.html" class="hover:text-purple-600 transition">Contact</a>
        <a href="https://wa.me/08038137679" class="bg-purple-600 text-white px-4 py-2 rounded-lg shadow hover:bg-purple-700 hover:scale-105 transition">WhatsApp</a>
      </nav>
      <div class="md:hidden">
        <button id="mobileBtn" class="text-2xl">☰</button>
      </div>
    </div>
    <div id="mobileMenu" class="hidden md:hidden bg-white/95 p-4 flex flex-col gap-2">
      <a href="index.html" class="font-semibold">Home</a>
      <a href="about.html">About</a>
      <a href="shop.html">Shop</a>
      <a href="contact.html">Contact</a>
      <a href="https://wa.me/08038137679" class="text-purple-600 font-semibold">WhatsApp</a>
    </div>
  </header>

  <!-- HERO SECTION -->
  <section class="grid md:grid-cols-2 items-center gap-6 max-w-7xl mx-auto py-16 px-6 fade-up">
    <div>
      <h1 class="text-5xl font-bold text-purple-600 leading-tight">Affordable & Luxury Fashion</h1>
      <p class="mt-4 text-lg text-gray-700 leading-relaxed">
        Welcome to SHOP W FAFA! We provide stylish accessories, hair clips, beads, luxury male & female wears, sundresses, shoes, and surprise gift packages. 
        Our products are crafted to make every customer feel elegant, confident, and unique.
      </p>
      <div class="flex flex-col sm:flex-row gap-3 mt-6">
        <a href="shop.html" class="bg-purple-600 text-white px-6 py-3 rounded-lg shadow hover:bg-purple-700 hover:scale-105 transition">Shop Now</a>
        <a href="about.html" class="text-purple-600 px-6 py-3 rounded-lg border border-purple-600 hover:bg-purple-50 transition">Learn More</a>
      </div>
    </div>
    <div>
      <img src="banner.jpg" alt="SHOP W FAFA Banner" class="w-full rounded-2xl shadow-fade hover-scale transition">
    </div>
  </section>

  <!-- FOUNDER MESSAGE -->
  <section class="bg-white py-16 px-6 fade-up">
    <div class="max-w-5xl mx-auto text-center">
      <h2 class="text-3xl font-bold text-purple-600 mb-4">A Message from Noah Faridat</h2>
      <p class="text-gray-700 leading-relaxed mb-2">
        "Fashion is a statement of confidence, style, and individuality. At SHOP W FAFA, we bring you affordable accessories and luxury wear that cater to modern trends while keeping quality in focus."
      </p>
      <p class="text-gray-700 leading-relaxed">
        Every item is chosen with care, and our worldwide shipping ensures our products reach you no matter where you are.
      </p>
    </div>
  </section>

  <!-- FEATURED PRODUCTS -->
  <section class="max-w-6xl mx-auto py-16 px-6 fade-up">
    <h2 class="text-3xl font-bold text-purple-600 text-center mb-8">Special Collection & Discounts</h2>
    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-6">
      <!-- PRODUCT 1 -->
      <article class="bg-white rounded-lg shadow hover-scale p-3">
        <img src="beads.jpg" alt="Beads 001" class="w-full h-48 object-cover rounded-lg mb-2">
        <h3 class="text-sm font-semibold">Beads 001</h3>
        <p class="text-xs text-gray-500 mt-1"></p>
        <button onclick="messageWhatsApp('Beads 001')" class="mt-2 bg-purple-600 text-white text-xs px-3 py-1 rounded hover:bg-purple-700 transition">Message</button>
      </article>
      <!-- PRODUCT 2 -->
      <article class="bg-white rounded-lg shadow hover-scale p-3">
        <img src="claw.jpg" alt="Hair Claw 002" class="w-full h-48 object-cover rounded-lg mb-2">
        <h3 class="text-sm font-semibold">Hair Claw 002</h3>
        <p class="text-xs text-gray-500 mt-1"></p>
        <button onclick="messageWhatsApp('Hair Claw 002')" class="mt-2 bg-purple-600 text-white text-xs px-3 py-1 rounded hover:bg-purple-700 transition">Message</button>
      </article>
      <!-- PRODUCT 3 -->
      <article class="bg-white rounded-lg shadow hover-scale p-3">
        <img src="chain.jpg" alt="Jean Chain 003" class="w-full h-48 object-cover rounded-lg mb-2">
        <h3 class="text-sm font-semibold">Jean Chain 003</h3>
        <p class="text-xs text-gray-500 mt-1"></p>
        <button onclick="messageWhatsApp('Jean Chain 003')" class="mt-2 bg-purple-600 text-white text-xs px-3 py-1 rounded hover:bg-purple-700 transition">Message</button>
      </article>

       <!-- PRODUCT 4 -->
      <article class="bg-white rounded-lg shadow hover-scale p-3">
        <img src="chains.jpg" alt="Neck Chain 004" class="w-full h-48 object-cover rounded-lg mb-2">
        <h3 class="text-sm font-semibold">Neck Chain 004</h3>
        <p class="text-xs text-gray-500 mt-1"></p>
        <button onclick="messageWhatsApp('Neck Chain 003')" class="mt-2 bg-purple-600 text-white text-xs px-3 py-1 rounded hover:bg-purple-700 transition">Message</button>
      </article>
      <!-- Repeat similarly for all 30 products with different names and discount prices -->
    </div>
  </section>

  <!-- TESTIMONIALS -->
  <section class="bg-purple-50 py-16 px-6 fade-up">
    <div class="max-w-5xl mx-auto text-center">
      <h2 class="text-3xl font-bold text-purple-600 mb-8">Customer Reviews</h2>
      <div class="grid md:grid-cols-3 gap-6">
        <div class="bg-white p-6 rounded-lg shadow">
          <p class="text-gray-700 mb-4">"I love my beads! Affordable and stylish, SHOP W FAFA never disappoints!"</p>
          <p class="font-semibold text-purple-600">- Aisha</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow">
          <p class="text-gray-700 mb-4">"The sundress I ordered arrived quickly and fits perfectly. Highly recommend!"</p>
          <p class="font-semibold text-purple-600">- Chinyere</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow">
          <p class="text-gray-700 mb-4">"Surprise gift packages are amazing. Great value and quality!"</p>
          <p class="font-semibold text-purple-600">- Fatima</p>
        </div>
      </div>
    </div>
  </section>

  <!-- GALLERY SECTION -->
  <section class="max-w-6xl mx-auto py-16 px-6 fade-up">
    <h2 class="text-3xl font-bold text-purple-600 text-center mb-8">Gallery</h2>
    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-4">
      <img src="clipp.jpg" alt="Hair Clip" class="rounded-lg hover-scale">
      <img src="bead.jpg" alt="Beads" class="rounded-lg hover-scale">
      <img src="shoe.jpg" alt="Shoes" class="rounded-lg hover-scale">
      <img src="sun.jpg" alt="Sundress" class="rounded-lg hover-scale">
      <img src="band.jpg" alt="Headband" class="rounded-lg hover-scale">
      <img src="holder.jpg" alt="Phone Holder" class="rounded-lg hover-scale">
      <img src="male.jpg" alt="Luxury Male Wear" class="rounded-lg hover-scale">
      <img src="git.jpg" alt="Gift Package" class="rounded-lg hover-scale">
      <img src="chain.jpg" alt="Jean Chain" class="rounded-lg hover-scale">
      <img src="claw.jpg" alt="Hair Claw" class="rounded-lg hover-scale">
    </div>
  </section>

  <!-- CALL TO ACTION -->
  <section class="bg-purple-100 py-16 text-center fade-up">
    <h2 class="text-3xl font-bold text-purple-600">Shop & Send a Gift Today!</h2>
    <p class="mt-4 text-gray-700 max-w-2xl mx-auto">Affordable fashion and luxury wear for all occasions. Surprise someone or treat yourself!</p>
    <a href="shop.html" class="mt-6 inline-block bg-purple-600 text-white px-8 py-4 rounded-lg shadow hover:bg-purple-700 hover:scale-105 transition">Explore Now</a>
  </section>

  <!-- FOOTER -->
  <footer class="bg-white mt-12 py-6 text-center text-gray-500">
    <p>© 2025 SHOP W FAFA | All Rights Reserved | Developed by VT DESIGNS</p>
  </footer>

  <!-- WHATSAPP CHAT BUTTON -->
  <a href="https://wa.me/08038137679" target="_blank"
     class="fixed right-5 bottom-5 bg-green-500 text-white p-4 rounded-full shadow-lg hover:scale-105 transition z-50">💬</a>

  <script>
    const btn = document.getElementById('mobileBtn');
    const mobileMenu = document.getElementById('mobileMenu');
    if(btn){ btn.addEventListener('click', ()=> mobileMenu.classList.toggle('hidden')); }

    const fadeElements = document.querySelectorAll('.fade-up');
    const observer = new IntersectionObserver(entries=>{
      entries.forEach(entry=>{
        if(entry.isIntersecting){ entry.target.classList.add('show'); }
      });
    },{threshold:0.2});
    fadeElements.forEach(el=>observer.observe(el));

    function messageWhatsApp(productName=''){
      const text = productName ? `Hello Noah Faridat, I'm interested in "${productName}". Please send details.` : 'Hello Noah Faridat, I need help.';
      window.open(`https://wa.me/08038137679?text=${encodeURIComponent(text)}`, '_blank');
    }
  </script>
</body>
</html>
