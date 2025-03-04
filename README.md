<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PENSION LUCERITO</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>PENSION LUCERITO</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#menu">Menú</a></li>
                <li><a href="#contacto">Contacto</a></li>
                <li><a href="#pedido">Hacer Pedido</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="inicio">
        <h2>Bienvenidos a PENSION LUCERITO</h2>
        <p>Te ofrecemos comida casera con el mejor sabor y calidad, en un ambiente acogedor y familiar.</p>
        <img src="images/restaurant.jpg" alt="Restaurante PENSION LUCERITO" width="100%">
    </section>
    
    <section id="menu">
        <h2>Nuestro Menú</h2>
        <ul>
            <li>🍽️ Almuerzo Completo (Lunes a Domingo)</li>
            <li>🔥 Chancho a la Cruz (Sábados y Domingos)</li>
            <li>🌙 Cena: Silpancho, Chuleta, Asado y Milanesa</li>
            <li>🥤 Refrescos y Cervezas</li>
        </ul>
        <img src="images/menu.jpg" alt="Menú de comidas" width="100%">
    </section>
    
    <section id="pedido">
        <h2>Hacer un Pedido</h2>
        <form action="#" method="POST">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>
            
            <label for="pedido">Pedido:</label>
            <textarea id="pedido" name="pedido" required></textarea>
            
            <label for="telefono">Teléfono:</label>
            <input type="tel" id="telefono" name="telefono" required>
            
            <h3>Métodos de Pago</h3>
            <p>📲 Pago QR</p>
            <p>💵 Efectivo (Bolivianos - Bs)</p>
            
            <button type="submit">Enviar Pedido</button>
        </form>
    </section>
    
    <section id="contacto">
        <h2>Contacto</h2>
        <p>📍 Dirección: Av. Capitán Víctor Ustáriz KM. 5, Cochabamba</p>
        <p>📞 Teléfono: +591 71789320</p>
        <p>📧 Email: contacto@deliciasexpress.com</p>
    </section>
    
    <footer>
        <p>© 2025 PENSION LUCERITO - Todos los derechos reservados.</p>
    </footer>
</body>
</html>

