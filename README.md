<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Página de Ventas con Menú Desplegable</title>
  <style>
    /* Reset básico */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #000000

;
      color: #000000;
    }

    /* Encabezado con menú */
    header {
      background-color: #000000;
      padding: 0.5rem 2rem;
    }

    /* Menu principal */
    nav ul {
      list-style: none;
      display: flex;
      align-items: center;
    }

    nav li {
      position: relative;
    }

    nav > ul > li {
      margin-right: 1.5rem;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      padding: 0.5rem 0.8rem;
      display: block;
      font-weight: bold;
    }

    nav a:hover {
      background-color: #1565C0;
      border-radius: 4px;
    }

    /* Dropdown */
    .dropdown {
      display: none;
      position: absolute;
      background-color: #1565C0;
      margin-top: 0.5rem;
      min-width: 150px;
      border-radius: 4px;
    }

    .dropdown li a {
      padding: 0.5rem 0.8rem;
    }

    nav li:hover .dropdown {
      display: block;
    }

    /* Título principal dentro del header */
    .site-title {
      color: #fff;
      font-size: 1.8rem;
      margin-left: auto; /* Empuja el título al centro */
    }

    /* Contenedor general */
    .container {
      max-width: 1100px;
      margin: 0 auto;
      padding: 2rem;
      background-color: #fff;
    }

    /* Sección de productos */
    .productos {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 2rem;
    }

    .producto {
      background-color: #f9f9f9;
      border: 1px solid #ddd;
      padding: 1.5rem;
      border-radius: 5px;
      text-align: center;
    }

    .producto h3 {
      color: #1E88E5;
      margin-bottom: 1rem;
    }

    .producto p {
      margin-bottom: 1.5rem;
    }

    /* Botón de WhatsApp */
    .whatsapp-btn {
      display: inline-flex;
      align-items: center;
      background-color: #25D366;
      color: #fff;
      text-decoration: none;
      border-radius: 4px;
      padding: 0.6rem 1rem;
      font-weight: bold;
      transition: background-color 0.3s ease;
    }

    .whatsapp-btn:hover {
      background-color: #20b957;
    }

    .whatsapp-btn img {
      height: 20px;
      width: 20px;
      margin-right: 0.5rem;
    }

    /* Estilo del pie de página */
    footer {
      background-color: #1E88E5;
      color: #fff;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    footer p {
      margin: 0;
    }
  </style>
</head>
<body>

  <!-- Encabezado con menú desplegable -->
  <header>
    <nav>
      <ul>
        <li><a href="#">TODO EN UN SOLO LUGAR</a></li>
        <li>
          <a href="#">STREAMINGJTL </a>
          <!-- Menú desplegable (dropdown) -->
          <ul class="dropdown">
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
          </ul>
        </li>
        <li><a href="https://wa.me/573186892091">WHATSAPP</a></li>
        <h1 class="site-title"></h1>
      </ul>
    </nav>
  </header>

  <!-- Sección: Productos -->
  <section class="container">
    <h2 style="text-align:center; color:#1E88E5; margin-bottom:2rem;"></h2>
    
    <!-- Producto 3 -->
      <div class="producto">
        <h3></h3>
        <img src="https://i.postimg.cc/nrVCFv0N/streaming.gif" alt="Descripción de Producto 3" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          
        </p>
        <a class="#" 
           href="#" 
           target="_blank">
        </a>
      </div>

    <div class="productos">
      <!-- Producto 1 -->
      <div class="producto">
        <h3>NETFLIX CUENTAS</h3>
        <img src="https://i.postimg.cc/cCdTGQGY/Netflix-Cuenta-Completa-5-perfiles-Colombia-1.png" alt="Descripción de Producto 1" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          Cuentas 100% originales para que puedan disfrutar de todo el contenido.

MODO ALQUILER USTED PAGARA MENSUALMENTE.

Beneficios:

Plataforma: Netflix Premium

Contenido en FHD

Garantía por el tiempo contratado

Soporte 24/7

Región: Global, esta cuenta esta liberada para usarse en todo el mundo


Nota: No cambiar ninguna información de la cuenta para que disfrute sin ningún inconveniente el servicio. si tienes alguna duda o consulta, envía un mensaje por: WhatsApp


        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20NETFLIX%20CUENTA%20COMPLETA%20$42500*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $42500
        </a>
      </div>
      
      <!-- Producto 2 -->
      <div class="producto">
        <h3>NETFLIX PANTALLAS</h3>
        <img src="https://i.postimg.cc/pdqLBvXH/Netflix-2-2-1.png" alt="Descripción de Producto 2" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          Cuentas 100% originales Facturacion con pines para que puedan disfrutar de todo el contenido.

MODO ALQUILER O TAMBIEN A SU DOMINIO  USTED PAGARA CADA 1 MES Y 28 DIAS 

Beneficios:

Plataforma: Netflix Premium
        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20PANTALLA%20DE%20NETFLIX%20$12000*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $12000
        </a>
      </div>

      <!-- Producto 3 -->
      <div class="producto">
        <h3>AMAZON PRIME VIDEO</h3>
        <img src="https://i.postimg.cc/CKLqrCBD/IMG-20250109-WA0005.jpg" alt="Descripción de Producto 3" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          Prime Video: 1 Mes – 1 Perfil
        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20PANTALLA%20PRIME%20VIDEO%20$8000*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $8000
        </a>
      </div>
      <div class="productos">
      <!-- Producto 1 -->
      <div class="producto">
        <h3>CRUNCHYROLL</h3>
        <img src="https://i.postimg.cc/5tjJcz9D/IMG-20250113-WA0056.jpg" alt="Descripción de Producto 1" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          Servicio: Crunchyroll Plus

Tiempo de suscripción: 1 Mes, 1 Perfil.

Dispositivos compatibles: Smart TV, Smartphone, Tablet, PC, Consolas.

*Sin afiliar tarjetas de crédito/débito.

*Cuentas Crunchyroll Plus por tiempo de vigencia predeterminado desde efectuada la compra.

*Entrega de credenciales a través de correo electrónico o WhatsApp del número registrado en su compra. 
        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20CRUNCHYROLL%20$7500*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $7500
        </a>
      </div>
      
      <!-- Producto 2 -->
      <div class="producto">
        <h3>DISNEY PLUS</h3>
        <img src="https://i.postimg.cc/wvf9ykfq/IMG-20241020-WA0023.jpg" alt="Descripción de Producto 2" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          Servicio: Disney Plus

Tiempo de suscripción: 1 Mes, 1 Perfil

Dispositivos compatibles: Smart TV, Smartphone, Tablet, PC, Consolas.

*Sin afiliar tarjetas de crédito/débito.

*Cuentas Disney Plus por tiempo de vigencia predeterminado desde efectuada la compra.

*Entrega de credenciales a través de correo electrónico o WhatsApp del número registrado en su compra.
        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20PANTALLA%20DISNEY+%20$8000*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $8000
        </a>
      </div>

      <!-- Producto 3 -->
      <div class="producto">
        <h3>HBO MAX</h3>
        <img src="https://i.postimg.cc/s2VXDV3R/IMG-20250113-WA0064.jpg" alt="Descripción de Producto 3" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          Servicio: MAX

Tiempo de suscripción: 1 Mes, 1 Perfil.

Dispositivos compatibles: Smart TV, Smartphone, Tablet, PC, Consolas.

*Sin afiliar tarjetas de crédito/débito.

*Cuentas HBO max por tiempo de vigencia predeterminado desde efectuada la compra

        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20HBO%20MAX%20$8000*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $8000
        </a>
      </div>
      
      <div class="productos">
      <!-- Producto 1 -->
      <div class="producto">
        <h3>PLEX</h3>
        <img src="https://i.postimg.cc/1tX3wJgC/IMG-20250113-WA0048.jpg" alt="Descripción de Producto 1" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          PLEX PLUS: 1 Mes – 1 Perfil 
        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20PLEX%20$7500*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $7500
        </a>
      </div>
      
      <!-- Producto 2 -->
      <div class="producto">
        <h3>IPTV</h3>
        <img src="https://i.postimg.cc/QNBprq6J/IMG-20250109-WA0010.jpg" alt="Descripción de Producto 2" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          Conexión Simultánea: Nuestro servicio permite el uso simultáneo en hasta 3 Dispositivos, asegurando entretenimiento para toda la familia.

IPTV  es una aplicación para ver películas, series, anime, fútbol en directo y dibujos animados en tu televisor Smart TV Samsung,LG , fire TV stick o smartphone, Apple IOS , Android TV, sin anuncios. Los usuarios pueden disfrutar de más de 1300 canales de televisión en vivo de forma gratuita y más de 280,000 horas de contenido VOD.
        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20IPTV%20PERFIL%20$15000*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $15000
        </a>
      </div>

      <!-- Producto 3 -->
      <div class="producto">
        <h3>VIX PLUS</h3>
        <img src="https://i.postimg.cc/c4wwvLGK/IMG-20250109-WA0008.jpg" alt="Descripción de Producto 3" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          Servicio: VíX Plus

Tiempo de suscripción: 1 Mes, Una Pantalla

Dispositivos compatibles: Smart TV, Smartphone, Tablet, PC, Consolas.

*Sin afiliar tarjetas de crédito/débito.

*Cuentas ViX Plus por tiempo de vigencia predeterminado desde efectuada la compra.
        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20VIX%20PLUS%20$7000*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $7000
        </a>
      </div>
      <div class="productos">
      <!-- Producto 1 -->
      <div class="producto">
        <h3>PARAMOUNT PLUS</h3>
        <img src="https://i.postimg.cc/Prs8nnvd/IMG-20250106-WA0013.jpg" alt="Descripción de Producto 1" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          Servicio: Paramount Plus

Tiempo de suscripción: 1 Mes, 1 Perfil

Dispositivos compatibles: Smart TV, Smartphone, Tablet, PC, Consolas.

*Sin afiliar tarjetas de crédito/débito.

*Cuentas Paramount Plus por tiempo de vigencia predeterminado desde efectuada la compra. 
        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20PARAMOUT%20PLUS%20$8000*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $8000
        </a>
      </div>
      
      <!-- Producto 2 -->
      <div class="producto">
        <h3>CANVA PRO</h3>
        <img src="https://i.postimg.cc/5tm41J8F/IMG-20250106-WA0045.jpg" alt="Descripción de Producto 2" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          CANVA PRO: 1 Mes – 1 Perfil
        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20CANVA%20$7500*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $7500
        </a>
      </div>

      <!-- Producto 3 -->
      <div class="producto">
        <h3>YOUTUBE PREMIUM</h3>
        <img src="https://i.postimg.cc/tgTsNXwN/IMG-20250106-WA0018.jpg" alt="Descripción de Producto 3" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          Servicio: Youtube Premium

Tiempo de suscripción: 1 Meses

Facturacion: 100% Legal

Contactar a Soporte despues de su pago


        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20YOUTUBE%20PREMIUM%20$8500*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $8500
        </a>
      </div>

<div class="productos">
      <!-- Producto 1 -->
      <div class="producto">
        <h3>EL PROFESOR.NET</h3>
        <img src="https://i.postimg.cc/g26N0Dtp/sdf.png" alt="Descripción de Producto 1" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>

ELPROFENET + WIN SPORTS


Descripción

🔰 DISPONIBLES PARA TV – CELULAR Y PC

Para Tv ingresa por el navegador web de tu smart tv a: elprofenet.co  cuando inicies sesión le das aceptar ventanas emergentes

Contenido
⚽ WIN SPORT +
⚽ DIRECTV SPORTS
🔰 Fox Sports
🔰 La Liga
🔰 ESPN

🗓️ DURACIÓN DE SU SERVICIO:  30 DIAS

 
        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20EL%20PROFE.NET%20$15000*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $15000
        </a>
      </div>
      
      <!-- Producto 2 -->
      <div class="producto">
        <h3>PORNHUB</h3>
        <img src="https://i.postimg.cc/pXBxBy49/pngwing-com.png" alt="Descripción de Producto 2" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          Descripción

1 pantalla de pornhub es una de las plataformas de videos porno más visitadas del mundo con duracion de 1 mes con mi correo TERMINOS si cambias el correo o contraseña se pierde la garantia 


        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20PORNHUB%20$10000*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $10000
        </a>
      </div>

      <!-- Producto 3 -->
      <div class="producto">
        <h3>MAGISTV</h3>
        <img src="https://i.postimg.cc/yd7wQC5V/3cb3d0c376c0fd32c75a84d70b2f40ab.jpg" alt="Descripción de Producto 3" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          "Descubre el Mundo de Emociones con Magis TV: ¡Tu Canal de Entretenimiento Favorito!"


        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20MAGISTV%20$15000" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $15000
        </a>
      </div>
      <div class="productos">
      <!-- Producto 1 -->
      <div class="producto">
        <h3>APPLE TV</h3>
        <img src="https://i.postimg.cc/6q3FKLtg/Apple-TV-logo.png" alt="Descripción de Producto 1" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          Servicio: Apple TV

Tiempo de suscripción: 1 Mes, Una cuenta Completa.

Dispositivos compatibles: Apple Tv: TV y PC (Web)

*Sin afiliar tarjetas de crédito/débito.

*Cuentas Apple Music por tiempo de vigencia predeterminado desde efectuada la compra. 
        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20APPLE%20TV%20$8000*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $8000
        </a>
      </div>
      
      
      
      <!-- Producto 2 -->
      <div class="producto">
        <h3>TIDAL</h3>
        <img src="https://i.postimg.cc/qqSyR4H0/tidal-high-fidelity-music-streaming-logo-vector.png" alt="Descripción de Producto 2" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>

Potencia de sonido a tu medida

110 millones de temas en HiRes FLAC y Dolby Atmos sin pérdida de sonido

Reproducción de contenido sin conexión y sin publicidad

Mixes personalizados, playlists creadas por nuestros editores y sesiones Live

DISPONIBLE
PERFIL Y CUENTA FAMILIAR
        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20CUENTA%20DE%20TIDAL%20PRO%20$10000*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $10000
        </a>
      </div>
      
     <!-- Producto 2 -->
      <div class="producto">
        <h3>NAPSTER</h3>
        <img src="https://i.postimg.cc/kgxKn013/Napster-Logo.png" alt="Descripción de Producto 2" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          Características de Napster Más de 110 millones de canciones sin publicidad, Listas de reproducción exclusivas, Radio curada, Vídeos musicales oficiales de artistas favoritos sin anuncios, Planes individuales y familiares.
        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20CUENTA%20DE%20NAPSTER%20PRO%20$10000*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $10000
        </a>
      </div> 
      
      <!-- Producto 2 -->
      <div class="producto">
        <h3>DIRECTV GO + WIN+

 </h3>
        <img src="https://i.postimg.cc/d1gcjJXL/dgo-win-1.png" alt="Descripción de Producto 2" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          DIRECTV GO + WIN 1 PANTALLA 1 MES
        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20DIRECTV%20GO%20BASICO%20CON%20WIN%201%20PANTALLA%20$15000*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $15000
        </a>
      </div> 
      
      <!-- Producto 2 -->
      <div class="producto">
        <h3>CLARO+</h3>
        <img src="https://i.postimg.cc/FHTqx9kN/CLARO-VIDEO-1-MES.png" alt="Descripción de Producto 2" style="max-width: 100%; height: auto; margin-bottom: 1rem;">
        <p>
          CLARO VIDEO + WIN+ (SIN CANALES EN VIVO) 1 MES
        </p>
        <a class="whatsapp-btn" 
           href="https://wa.me/573207680836?text=*COMPRAR%20CLARO%20VIDEO+WIN%20(SIN%20CANALES%20EN%20VIVO%20$15000*" 
           target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp icon">
          $15000
        </a>
      </div> 
      
      <!-- Producto 2 -->
      
      
      <!-- Producto 2 -->
      <d
