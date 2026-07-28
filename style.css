/* ================= VARIÁVEIS & RESET ================= */
:root {
    --verde-escuro: #1A4321;
    --verde-primario: #2E7D32;
    --verde-claro: #81C784;
    --fundo: #F4F7F6;
    --texto: #333333;
    --texto-claro: #666666;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
    font-family: 'Inter', sans-serif;
    background-color: var(--fundo);
    color: var(--texto);
}

h1, h2, h3, .logo {
    font-family: 'Poppins', sans-serif;
}

/* ================= HEADER NAVBAR ================= */
header {
    position: fixed;
    top: 0;
    width: 100%;
    background: rgba(255, 255, 255, 0.95);
    backdrop-filter: blur(10px);
    box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    z-index: 1000;
    transition: all 0.3s ease;
}

.nav-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 1.5rem;
    color: var(--verde-primario);
    font-weight: 700;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 25px;
}

nav a {
    text-decoration: none;
    color: var(--texto);
    font-weight: 500;
    transition: color 0.3s;
    font-size: 1rem;
}

nav a:hover, nav a.active {
    color: var(--verde-primario);
    font-weight: 700;
}

/* ================= HERO SECTION ================= */
.hero {
    height: 100vh;
    background: linear-gradient(rgba(26, 67, 33, 0.7), rgba(46, 125, 50, 0.6)), 
                url('https://images.unsplash.com/photo-1625246333195-78d9c38ad449?q=80&w=1920&auto=format&fit=crop') center/cover;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: white;
    padding: 0 20px;
}

.hero-content {
    max-width: 800px;
    margin-top: 60px; /* Compensa o menu */
}

.hero h1 {
    font-size: 4rem;
    margin-bottom: 20px;
    line-height: 1.2;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 30px;
    font-weight: 400;
}

.btn-primary {
    display: inline-block;
    padding: 15px 30px;
    background-color: var(--verde-claro);
    color: var(--verde-escuro);
    text-decoration: none;
    font-weight: 700;
    border-radius: 30px;
    transition: transform 0.3s, background 0.3s;
}

.btn-primary:hover {
    background-color: white;
    transform: translateY(-3px);
}

/* ================= MAIN LAYOUT ================= */
main {
    max-width: 1200px;
    margin: 0 auto;
    padding: 40px 20px;
}

section {
    padding: 80px 0;
}

h2 {
    font-size: 2.2rem;
    color: var(--verde-escuro);
    margin-bottom: 20px;
}

p {
    font-size: 1.1rem;
    line-height: 1.8;
    color: var(--texto-claro);
}

.text-center {
    text-align: center;
    max-width: 700px;
    margin: 0 auto 50px auto;
}

/* ================= SEÇÕES DUPLAS (Texto + Imagem) ================= */
.secao-dupla {
    display: flex;
    align-items: center;
    gap: 50px;
}

.secao-dupla.reverse {
    flex-direction: row-reverse;
}

.secao-dupla .texto, .secao-dupla .imagem {
    flex: 1;
}

.secao-dupla img {
    width: 100%;
    border-radius: 20px;
    box-shadow: 0 15px 30px rgba(0,0,0,0.1);
    object-fit: cover;
    max-height: 400px;
}

/* ================= CARDS DOS PILARES ================= */
.pilares-cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
}

.pilar-item {
    background: white;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(0,0,0,0.05);
    transition: transform 0.3s, box-shadow 0.3s;
}

.pilar-item:hover {
    transform: translateY(-10px);
    box-shadow: 0 15px 30px rgba(0,0,0,0.1);
}

.pilar-item img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.pilar-conteudo {
    padding: 25px;
}

.pilar-conteudo h3 {
    color: var(--verde-primario);
    font-size: 1.3rem;
    margin-bottom: 10px;
}

.pilar-conteudo p {
    font-size: 1rem;
}

/* ================= FOOTER ================= */
footer {
    background-color: var(--verde-escuro);
    color: white;
    text-align: center;
    padding: 30px 20px;
    font-size: 0.9rem;
}

/* ================= RESPONSIVO ================= */
@media (max-width: 768px) {
    .nav-container {
        flex-direction: column;
        gap: 15px;
    }
    .hero h1 {
        font-size: 2.5rem;
    }
    .secao-dupla, .secao-dupla.reverse {
        flex-direction: column;
    }
    section {
        padding: 50px 0;
    }
}

/* ================= ANIMAÇÕES JS ================= */
.hidden {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.8s ease-out, transform 0.8s ease-out;
}

.show {
    opacity: 1;
    transform: translateY(0);
}
