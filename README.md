# torexpress.github.io
TRANSPORT SERVICES SOLUTIONS
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TOR EXPRESS - Soluciones de Transporte</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- ================= HERO / HOME ================= -->
    <header class="hero">
        <div class="container">
            <h1>Soluciones de transporte rápidas, fiables y adaptadas a tu negocio.</h1>
            <p>Servicio nacional e internacional con respuesta inmediata y atención directa.</p>

            <div class="hero-buttons">
                <a href="#contacto" class="btn">Solicitar presupuesto</a>
                <a href="#proveedores" class="btn btn-outline">Colaborar como proveedor</a>
            </div>

            <div class="hero-features">
                <div class="feature">
                    <h3>Transporte Nacional</h3>
                    <p>Cobertura completa en toda España con recogidas flexibles y entregas puntuales.</p>
                </div>
                <div class="feature">
                    <h3>Transporte Internacional</h3>
                    <p>Operativa en Europa con seguimiento continuo y comunicación transparente.</p>
                </div>
                <div class="feature">
                    <h3>Urgentes 24/7</h3>
                    <p>Cuando cada minuto cuenta, ofrecemos soluciones inmediatas y personalizadas.</p>
                </div>
            </div>
        </div>
    </header>

    <!-- ================= SERVICIOS ================= -->
    <section id="servicios" class="section">
        <div class="container">
            <h2>Servicios</h2>

            <div class="grid">
                <div class="card">
                    <h3>Transporte Nacional</h3>
                    <p>Gestionamos envíos en todo el territorio nacional con rapidez, puntualidad y un trato cercano.</p>
                </div>

                <div class="card">
                    <h3>Transporte Internacional</h3>
                    <p>Soluciones de transporte por carretera en Europa para cargas completas y parciales.</p>
                </div>

                <div class="card">
                    <h3>Urgentes 24/7</h3>
                    <p>Disponibilidad inmediata para envíos críticos con entrega garantizada en el menor tiempo posible.</p>
                </div>

                <div class="card">
                    <h3>Distribución y Grupaje</h3>
                    <p>Opciones eficientes para envíos recurrentes o cargas compartidas.</p>
                </div>

                <div class="card">
                    <h3>Servicio Personalizado</h3>
                    <p>Diseñamos soluciones a medida según el tipo de mercancía, destino y urgencia.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= ÁREAS DE OPERACIÓN ================= -->
    <section id="areas" class="section section-light">
        <div class="container">
            <h2>Áreas de Operación</h2>

            <div class="grid">
                <div class="card">
                    <h3>Cataluña</h3>
                    <p>Recogidas diarias y servicio flexible en toda la comunidad.</p>
                </div>

                <div class="card">
                    <h3>Península Ibérica</h3>
                    <p>Cobertura completa en España y Portugal con colaboradores de confianza.</p>
                </div>

                <div class="card">
                    <h3>Europa</h3>
                    <p>Transporte internacional con tiempos de tránsito ajustados y máxima fiabilidad.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= SOLUCIONES PARA EMPRESAS ================= -->
    <section id="soluciones" class="section">
        <div class="container">
            <h2>Soluciones para Empresas</h2>

            <div class="grid">
                <div class="card">
                    <h3>Industria</h3>
                    <p>Transporte seguro y puntual para mercancías sensibles o urgentes.</p>
                </div>

                <div class="card">
                    <h3>E-commerce y Logística</h3>
                    <p>Soluciones rápidas y adaptadas a picos de demanda.</p>
                </div>

                <div class="card">
                    <h3>Distribuidores</h3>
                    <p>Rutas regulares, entregas programadas y gestión optimizada de cargas.</p>
                </div>

                <div class="card">
                    <h3>Pequeñas Empresas</h3>
                    <p>Servicio flexible, sin mínimos y con atención personalizada.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= PROVEEDORES ================= -->
    <section id="proveedores" class="section section-light">
        <div class="container">
            <h2>Únete a nuestra red de transportistas</h2>
            <p>Buscamos profesionales comprometidos para ampliar nuestra red de colaboradores. Ofrecemos comunicación clara, pagos puntuales y rutas constantes.</p>
            <a href="#contacto" class="btn">Unirme como proveedor</a>
        </div>
    </section>

    <!-- ================= SOBRE NOSOTROS ================= -->
    <section id="nosotros" class="section">
        <div class="container">
            <h2>Sobre Nosotros</h2>
            <p>
                TOR EXPRESS es una empresa orientada a ofrecer soluciones de transporte rápidas, eficientes y adaptadas a cada cliente.
                Creemos en el trato directo, la puntualidad y la confianza como base de cada envío.
                Nuestro objetivo es convertirnos en tu socio logístico de referencia.
            </p>
        </div>
    </section>

    <!-- ================= CONTACTO ================= -->
    <section id="contacto" class="section section-light">
        <div class="container">
            <h2>Contacto</h2>
            <p>Cuéntanos qué necesitas y te ofreceremos la solución más adecuada.</p>

            <ul class="contact-info">
                <li><strong>Teléfono:</strong> +34 667 67 24 16</li>
                <li><strong>Email:</strong> victor@torexpress.net</li>
            </ul>

            <form class="contact-form">
                <input type="text" placeholder="Nombre" required>
                <input type="text" placeholder="Empresa">
                <input type="tel" placeholder="Teléfono">
                <input type="email" placeholder="Email" required>
                <textarea placeholder="Mensaje" required></textarea>
                <button type="submit" class="btn">Enviar</button>
            </form>
        </div>
    </section>

    /* ===========================
   ESTILOS GENERALES
=========================== */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body {
    color: #333;
    background-color: #f7f7f7;
    line-height: 1.6;
}

.container {
    width: 90%;
    max-width: 1100px;
    margin: auto;
}

.section {
    padding: 60px 0;
}

.section-light {
    background-color: #ffffff;
}

h1, h2, h3 {
    margin-bottom: 15px;
    font-weight: 700;
}

p {
    margin-bottom: 15px;
    color: #555;
}

/* ===========================
   BOTONES
=========================== */

.btn {
    display: inline-block;
    padding: 12px 25px;
    background-color: #005bbb;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 10px;
    transition: 0.3s;
}

.btn:hover {
    background-color: #004999;
}

.btn-outline {
    background-color: transparent;
    border: 2px solid #005bbb;
    color: #005bbb;
}

.btn-outline:hover {
    background-color: #005bbb;
    color: #fff;
}

/* ===========================
   HERO / HOME
=========================== */

.hero {
    background: linear-gradient(to bottom right, #005bbb, #003f7f);
    color: #fff;
    padding: 100px 0;
    text-align: center;
}

.hero p {
    color: #e6e6e6;
}

.hero-buttons {
    margin: 25px 0;
}

.hero-buttons .btn {
    margin: 5px;
}

.hero-features {
    display: flex;
    justify-content: center;
    gap: 25px;
    margin-top: 40px;
    flex-wrap: wrap;
}

.feature {
    background-color: rgba(255, 255, 255, 0.1);
    padding: 20px;
    border-radius: 8px;
    width: 280px;
}

/* ===========================
   GRID GENERAL
=========================== */

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 25px;
    margin-top: 30px;
}

.card {
    background-color: #fff;
    padding: 25px;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.08);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
}

/* ===========================
   CONTACTO
=========================== */

.contact-info {
    list-style: none;
    margin-bottom: 25px;
}

.contact-info li {
    margin-bottom: 8px;
}

.contact-form {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 15px;
}

.contact-form input,
.contact-form textarea {
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.contact-form textarea {
    grid-column: span 2;
    height: 120px;
}

.contact-form button {
    grid-column: span 2;
}

/* ===========================
   RESPONSIVE
=========================== */

@media (max-width: 768px) {
    .hero {
        padding: 70px 20px;
    }

    .contact-form {
        grid-template-columns: 1fr;
    }

    .contact-form textarea,
    .contact-form button {
        grid-column: span 1;
    }
}

</body>
</html>