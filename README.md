# prova![logo-bz-beige png](https://github.com/user-attachments/assets/0e875088-3926-4bc2-a043-5839af943c03)
![logo-bz-beige png](https://github.com/user-attachments/assets/0e875088-3926-4bc2-a043-5839af943c03)
body {
  font-family: 'Montserrat', Arial, sans-serif;
  margin: 0;
  background: #f5f5dc;
  color: #222;
}

.navbar {
  background: #fff;
  box-shadow: 0 2px 8px #0001;
  position: sticky;
  top: 0;
  z-index: 10;
}

.navbar-content {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1.2em 2em;
}

.logo-brand {
  display: flex;
  align-items: center;
  gap: 0.7em;
  font-weight: bold;
  color: #388e3c;
  font-size: 1.2em;
}
.logo {
  height: 44px; width: 44px; border-radius: 10px; background: #f5f5dc;
}

nav a {
  text-decoration: none;
  color: #222;
  margin: 0 1.1em;
  font-weight: 500;
  transition: color 0.2s;
}
nav a:hover { color: #388e3c; }

.filter-bar {
  display: flex;
  justify-content: center;
  padding: 2em 0 1.2em 0;
  background: #fff8e1;
  box-shadow: 0 2px 12px #0001;
}

.search-bar {
  padding: 1em;
  border: 1.5px solid #c6c2a1;
  border-radius: 25px;
  width: 340px;
  font-size: 1.1em;
  background: #f8f7ef;
}

.catalog-section {
  max-width: 1250px;
  margin: 2.5em auto;
  padding: 0 1.2em;
}
.catalog-section h2 {
  font-size: 2em;
  margin-bottom: 1.4em;
  color: #388e3c;
}
.catalog-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px,1fr));
  gap: 2.1em;
}

.catalog-card {
  background: #fff;
  border-radius: 23px;
  box-shadow: 0 4px 20px #0002;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  transition: box-shadow 0.2s, transform 0.2s;
  border: 1px solid #eee;
}
.catalog-card img {
  width: 100%;
  height: 178px;
  object-fit: cover;
  border-bottom: 1px solid #eee;
}
.card-body {
  padding: 1.1em 1em 1em 1em;
  display: flex;
  flex-direction: column;
  gap: 0.6em;
}
.card-title {
  font-size: 1.07em;
  font-weight: bold;
  color: #388e3c;
  margin-bottom: 0.2em;
}
.card-desc {
  font-size: 0.99em;
  color: #444;
  margin-bottom: 0.4em;
}
.card-footer {
  display: flex;
  align-items: center;
  gap: 1em;
  margin-top: 0.4em;
}
.card-link {
  background: #388e3c;
  color: #fff;
  padding: 0.5em 1.2em;
  border-radius: 22px;
  text-decoration: none;
  font-weight: 600;
  font-size: 1em;
  transition: background 0.2s;
}
.card-link:hover { background: #2e7d32; }
.card-badge {
  background: #388e3c;
  color: #fff;
  border-radius: 12px;
  padding: 0.2em 1em;
  font-size: 0.89em;
  font-weight: 700;
  letter-spacing: 0.03em;
}
.badge-green { background: #6eb77a; }
.badge-beige { background: #ede8d7; color: #444; }

.catalog-card:hover {
  box-shadow: 0 10px 38px #0002;
  transform: translateY(-7px) scale(1.02);
}

.about-section, .contact-section {
  max-width: 800px;
  margin: 2.5em auto 1.5em auto;
  background: #fff;
  border-radius: 18px;
  box-shadow: 0 2px 12px #0001;
  padding: 2em;
}

.contact-form {
  display: flex;
  flex-direction: column;
  gap: 1em;
  margin-top: 1em;
}
.contact-form label {
  font-weight: 600;
}
.contact-form input, .contact-form textarea {
  width: 100%;
  padding: 0.6em;
  border-radius: 7px;
  border: 1px solid #b2dfdb;
  font-size: 1em;
  margin-top: 0.3em;
  margin-bottom: 0.7em;
}
.contact-form button {
  background: #388e3c;
  color: #fff;
  border: none;
  padding: 0.8em 2em;
  border-radius: 28px;
  font-size: 1.08em;
  font-weight: bold;
  cursor: pointer;
  align-self: flex-start;
  transition: background 0.2s;
}
.contact-form button:hover { background: #2e7d32; }

footer {
  background: #282c22;
  color: #fff8e1;
  text-align: center;
  padding: 2em 0 1.2em 0;
  font-size: 1em;
  margin-top: 2em;
}
.footer-logo {
  height: 34px;
  margin-bottom: 1em;
  border-radius: 8px;
  background: #f5f5dc;
}

@media (max-width: 900px) {
  .navbar-content, .catalog-section { padding: 0 0.7em; }
  .about-section, .contact-section { padding: 1em; }
}
@media (max-width: 700px) {
  .navbar-content { flex-direction: column; align-items: flex-start; gap: 1em; }
  nav { margin: 0.5em 0; }
  .catalog-grid { grid-template-columns: 1fr; }
  .catalog-section h2 { font-size: 1.25em; }
}<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BZ Consulting Ltda. – Catálogo de Invernaderos</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://fonts.googleapis.com/css?family=Montserrat:400,700&display=swap" rel="stylesheet">
</head>
<body>
  <header class="navbar">
    <div class="navbar-content">
      <div class="logo-brand">
        <img src="logo-bz-beige.png" alt="Logo BZ" class="logo">
        <span>BZ Consulting Ltda.</span>
      </div>
      <nav>
        <a href="#catalog">Catálogo</a>
        <a href="#about">Quiénes somos</a>
        <a href="#contact">Contacto</a>
      </nav>
    </div>
  </header>

  <!-- Filtro estilo Airbnb -->
  <section class="filter-bar">
    <input type="text" id="searchInput" class="search-bar" placeholder="Buscar producto, tipo, o material..." onkeyup="filterProducts()">
  </section>

  <!-- Catálogo de productos -->
  <main>
    <section id="catalog" class="catalog-section">
      <h2>Catálogo de Invernaderos y Soluciones Agrícolas</h2>
      <div class="catalog-grid" id="productsGrid">
        <!-- Tarjetas de producto -->
        <div class="catalog-card">
          <img src="https://www.lightdeprivation-greenhouse.com/images/products/Light-Deprivation-Greenhouse-1.jpg" alt="Invernadero de Privación de Luz">
          <div class="card-body">
            <div class="card-title">Invernadero de Privación de Luz</div>
            <div class="card-desc">Oscurecimiento automático, estructura profesional, ideal cáñamo y floricultura.</div>
            <div class="card-footer">
              <span class="card-badge">Premium</span>
              <a href="https://www.lightdeprivation-greenhouse.com/light-deprivation-greenhouse.html" class="card-link" target="_blank">Ver más</a>
            </div>
          </div>
        </div>
        <div class="catalog-card">
          <img src="https://www.lightdeprivation-greenhouse.com/images/products/Auto-Blackout-Greenhouse-1.jpg" alt="Invernadero de Apagón Automático">
          <div class="card-body">
            <div class="card-title">Invernadero de Apagón Automático</div>
            <div class="card-desc">Control total de luz, cortinas motorizadas y ventilación avanzada.</div>
            <div class="card-footer">
              <span class="card-badge badge-green">Top ventas</span>
              <a href="https://www.lightdeprivation-greenhouse.com/auto-blackout-greenhouse.html" class="card-link" target="_blank">Ver más</a>
            </div>
          </div>
        </div>
        <div class="catalog-card">
          <img src="https://www.lightdeprivation-greenhouse.com/images/products/Polycarbonate-Greenhouse-1.jpg" alt="Invernadero de Policarbonato">
          <div class="card-body">
            <div class="card-title">Invernadero de Policarbonato</div>
            <div class="card-desc">Aislación térmica, máxima durabilidad, ideal climas extremos.</div>
            <div class="card-footer">
              <span class="card-badge badge-beige">Nuevo</span>
              <a href="https://www.lightdeprivation-greenhouse.com/polycarbonate-greenhouse.html" class="card-link" target="_blank">Ver más</a>
            </div>
          </div>
        </div>
        <div class="catalog-card">
          <img src="https://www.lightdeprivation-greenhouse.com/images/products/Multi-Span-Greenhouse-1.jpg" alt="Invernadero Multicapilla">
          <div class="card-body">
            <div class="card-title">Invernadero Multicapilla</div>
            <div class="card-desc">Diseño modular, superficie de cultivo ampliada, ventilación y eficiencia energética.</div>
            <div class="card-footer">
              <span class="card-badge">Pro</span>
              <a href="https://www.lightdeprivation-greenhouse.com/multi-span-greenhouse.html" class="card-link" target="_blank">Ver más</a>
            </div>
          </div>
        </div>
        <div class="catalog-card">
          <img src="https://www.lightdeprivation-greenhouse.com/images/products/Glass-Greenhouse-1.jpg" alt="Invernadero de Vidrio">
          <div class="card-body">
            <div class="card-title">Invernadero de Vidrio (Venlo)</div>
            <div class="card-desc">Máxima transparencia, durabilidad y control climático, ideal para cultivos de alto valor.</div>
            <div class="card-footer">
              <span class="card-badge badge-beige">Premium</span>
              <a href="https://www.lightdeprivation-greenhouse.com/glass-greenhouse.html" class="card-link" target="_blank">Ver más</a>
            </div>
          </div>
        </div>
        <div class="catalog-card">
          <img src="https://www.lightdeprivation-greenhouse.com/images/products/Tunnel-Greenhouse-1.jpg" alt="Invernadero Túnel">
          <div class="card-body">
            <div class="card-title">Invernadero Túnel</div>
            <div class="card-desc">Estructura simple, económica y eficiente para todo tipo de cultivos.</div>
            <div class="card-footer">
              <span class="card-badge">Económico</span>
              <a href="https://www.lightdeprivation-greenhouse.com/tunnel-greenhouse.html" class="card-link" target="_blank">Ver más</a>
            </div>
          </div>
        </div>
        <!-- Puedes agregar más cards según tu catálogo -->
      </div>
    </section>

    <section id="about" class="about-section">
      <h2>Quiénes Somos</h2>
      <p>En <strong>BZ Consulting Ltda.</strong> acercamos tecnología y soluciones agrícolas de primer nivel con asesoría personalizada y soporte integral.</p>
    </section>

    <section id="contact" class="contact-section">
      <h2>Contacto</h2>
      <form class="contact-form">
        <label>Nombre: <input type="text" required></label>
        <label>Email: <input type="email" required></label>
        <label>Mensaje: <textarea required></textarea></label>
        <button type="submit">Enviar</button>
      </form>
    </section>
  </main>
  <footer>
    <img src="logo-bz-beige.png" alt="BZ Logo" class="footer-logo">
    <p>&copy; 2025 BZ Consulting Ltda.</p>
  </footer>
  <script>
    function filterProducts() {
      const input = document.getElementById('searchInput').value.toLowerCase();
      const cards = document.getElementById('productsGrid').getElementsByClassName('catalog-card');
      for (let card of cards) {
        const text = card.innerText.toLowerCase();
        card.style.display = text.includes(input) ? '' : 'none';
      }
    }
  </script>
</body>
</html>
