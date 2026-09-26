# proyecto-final-part-1
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arte, Creación y Manualidades</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>

    <header class="navbar">
        <div class="logo">
            <div class="logo-ac">AC</div>
            <div class="logo-text">
                <span>Arte, Creación</span>
                <small>y Manualidades</small>
            </div>
        </div>

        <nav>
            <a href="#inicio">Inicio</a>
            <a href="#arte">Arte</a>
            <a href="#manualidades">Manualidades</a>
            <a href="#nosotros">Nosotros</a>
            <a href="#contacto">Contacto</a>
        </nav>

        <div class="redes">
            <a href="#">◎</a>
            <a href="#">f</a>
            <a href="#">◉</a>
        </div>
    </header>

    <main id="inicio">

        <section class="hero">
            <div class="contenido-hero">
                <p class="bienvenida">Bienvenidos a</p>
                <h1>Arte, Creación<br>y Manualidades</h1>
                <div class="decoracion">───────── ✿ ─────────</div>
                <p class="descripcion">
                    Un espacio para compartir, crear y descubrir nuevas formas de expresar nuestra creatividad.
                </p>
                <a href="#arte" class="boton">Explorar ahora →</a>
            </div>
        </section>

        <section class="categorias">
            <div class="tarjeta" id="arte">
                <div class="icono">🎨</div>
                <div>
                    <h2>Arte</h2>
                    <p>Descubre tutoriales, cursos, dibujos, pinturas y mucho más.</p>
                    <a href="#">Ver sección de Arte →</a>
                </div>
            </div>

            <div class="tarjeta" id="manualidades">
                <div class="icono">🧶</div>
                <div>
                    <h2>Manualidades</h2>
                    <p>Encuentra manualidades hechas con amor y productos disponibles para ti.</p>
                    <a href="#">Ver manualidades →</a>
                </div>
            </div>
        </section>

        <section class="nosotros" id="nosotros">
            <h2>Sobre nosotros</h2>
            <p>
                En Arte, Creación y Manualidades creemos que cada creación tiene una historia.
                Este es un espacio para compartir talento, imaginación y creatividad.
            </p>
        </section>

        <section class="contacto" id="contacto">
            <div>
                ☎️
                <span>
                    Número de contacto
                    <strong>300 000 0000</strong>
                </span>
            </div>

            <div>
                💬
                <span>
                    WhatsApp
                    <strong>300 000 0000</strong>
                </span>
            </div>

            <div>
                ✉️
                <span>
                    Escríbenos
                    <strong>En nuestras redes sociales</strong>
                </span>
            </div>
        </section>

    </main>

    <footer>
        <p>© 2026 Arte, Creación y Manualidades</p>
    </footer>

</body>
</html>

<link rel="stylesheet" href="styles.css">{
    margin: 0;
    padding: 0;
    box-sizing: border-box;

<a {
    scroll-behavior: smooth;
}

body {
    font-family: Georgia, serif;
    background: #160b15;
    color: #f8e8e8;
}
></a>
/* =========================
 
MENÚ
========================= */

.navbar {
    height: 105px;
    background: #100a10;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 15px 5%;
    border-bottom: 1px solid #613044;
    position: sticky;
    top: 0;
    z-index: 1000;
}

/* LOGO */

.logo {
    display: flex;
    align-items: center;
    gap: 15px;
}

.logo-ac {
    width: 70px;
    height: 70px;
    border: 2px solid #c97991;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: Georgia, serif;
    font-size: 30px;
    color: #e4a1b2;
}

.logo-text {
    display: flex;
    flex-direction: column;
}

.logo-text span {
    color: #d8849d;
    font-size: 20px;
    font-style: italic;
}

.logo-text small {
    color: white;
    font-size: 14px;
    text-align: center;
}

/* MENÚ DE NAVEGACIÓN */

nav {
    display: flex;
    gap: 35px;
}

nav a {
    color: #f5dddd;
    text-decoration: none;
    font-size: 17px;
    transition: 0.3s;
}

nav a:hover {
    color: #d97896;
}

/* REDES SOCIALES */

.redes {
    display: flex;
    gap: 15px;
}

.redes a {
    width: 38px;
    height: 38px;
    border-radius: 50%;
    background: #a94c6c;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    text-decoration: none;
}

/* =========================
   PORTADA
========================= */

.hero {
    min-height: 650px;
    display: flex;
    align-items: center;
    padding: 80px 12%;
    background-image:
        linear-gradient(
            rgba(25, 8, 23, 0.45),
            rgba(25, 8, 23, 0.60)
        ),
        url("imagenes/fondo-arte.png");
    background-size: cover;
    background-position: center;
    position: relative;
}

.contenido-hero {
    max-width: 650px;
}

.bienvenida {
    color: #d97e97;
    font-size: 28px;
    margin-bottom: 10px;
}

h1 {
    font-size: 62px;
    line-height: 1.05;
    color: #fff0e8;
    font-weight: normal;
}

.decoracion {
    color: #d8879d;
    margin: 25px 0;
    font-size: 18px;
}

.descripcion {
    font-size: 20px;
    line-height: 1.6;
    color: #f0dfe3;
    max-width: 450px;
    margin-bottom: 30px;
}

/* BOTÓN */

.boton {
    display: inline-block;
    padding: 15px 35px;
    border-radius: 35px;
    background: #b92f62;
    color: white;
    text-decoration: none;
    font-size: 18px;
    border: 1px solid #e9a1b4;
    transition: 0.3s;
}

.boton:hover {
    background: #d34878;
    transform: translateY(-3px);
}

/* =========================
   TARJETAS
========================= */

.categorias {
    display: flex;
    justify-content: center;
    gap: 30px;
    padding: 60px 8%;
    background: #180b17;
}

.tarjeta {
    width: 500px;
    min-height: 180px;
    padding: 30px;
    display: flex;
    align-items: center;
    gap: 25px;
    border: 1px solid #75405a;
    border-radius: 20px;
    background: rgba(35, 15, 31, 0.95);
    box-shadow: 0 10px 30px rgba(0,0,0,0.4);
    transition: 0.3s;
}

.tarjeta:hover {
    transform: translateY(-5px);
    border-color: #c66b87;
}

.icono {
    width: 75px;
    height: 75px;
    border: 1px solid #c56c86;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 35px;
    flex-shrink: 0;
}

.tarjeta h2 {
    color: #d47b96;
    font-size: 30px;
    margin-bottom: 10px;
}

.tarjeta p {
    color: #eadcdf;
    line-height: 1.5;
    margin-bottom: 15px;
}

.tarjeta a {
    color: #e68da5;
    text-decoration: underline;
    font-weight: bold;
}

/* =========================
   NOSOTROS
========================= */

.nosotros {
    text-align: center;
    padding: 80px 20%;
    background: #241021;
}

.nosotros h2 {
    font-size: 38px;
    color: #d8849c;
    margin-bottom: 20px;
}

.nosotros p {
    font-size: 19px;
    line-height: 1.8;
    color: #eadfe2;
}

/* =========================
   CONTACTO
========================= */

.contacto {
    display: flex;
    justify-content: center;
    gap: 80px;
    padding: 35px;
    background: #100a10;
}

.contacto div {
    display: flex;
    align-items: center;
    gap: 15px;
    color: #d8819b;
    font-size: 25px;
}

.contacto span {
    display: flex;
    flex-direction: column;
    font-size: 14px;
    color: #cdbbc0;
}

.contacto strong {
    color: white;
    margin-top: 5px;
}

/* =========================
   FOOTER
========================= */

footer {
    text-align: center;
    padding: 25px;
    background: #090609;
    color: #98878d;
}

/* =========================
   ADAPTACIÓN MÓVIL
========================= */

@media (max-width: 900px) {
    .navbar {
        height: auto;
        flex-direction: column;
        gap: 20px;
    }

    nav {
        gap: 15px;
        flex-wrap: wrap;
        justify-content: center;
    }

    .hero {
        padding: 70px 8%;
    }

    h1 {
        font-size: 45px;
    }

    .categorias {
        flex-direction: column;
    }

    .tarjeta {
        width: 100%;
    }

    .contacto {
        flex-direction: column;
        gap: 25px;
    }
}
