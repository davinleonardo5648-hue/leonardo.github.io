# leonardo.github.io
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Doce Páscoa | Ovos Artesanais</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins', sans-serif;
}

body{
    background:#fff;
    color:#333;
}

header{
    background:#8B0000;
    padding:20px 10%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    color:white;
}

header h1{
    font-size:24px;
}

header nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
    font-weight:500;
}

.hero{
    background:linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.5)),
    url('https://images.unsplash.com/photo-1587248720327-8eb72564be1e');
    background-size:cover;
    background-position:center;
    height:80vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    color:white;
    padding:20px;
}

.hero h2{
    font-size:42px;
    margin-bottom:20px;
}

.btn{
    background:#FFD700;
    padding:12px 25px;
    border-radius:30px;
    text-decoration:none;
    color:#000;
    font-weight:600;
}

.section{
    padding:70px 10%;
    text-align:center;
}

.section h2{
    margin-bottom:40px;
    font-size:32px;
    color:#8B0000;
}

.produtos{
    display:grid;
    grid-template-columns:repeat(auto-fit, minmax(250px,1fr));
    gap:30px;
}

.card{
    background:#fff;
    border-radius:15px;
    box-shadow:0 10px 20px rgba(0,0,0,0.08);
    padding:20px;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-5px);
}

.card img{
    width:100%;
    border-radius:10px;
}

.preco{
    font-size:20px;
    font-weight:600;
    margin:10px 0;
    color:#8B0000;
}

.whatsapp-btn{
    display:inline-block;
    background:#25D366;
    color:white;
    padding:10px 20px;
    border-radius:20px;
    text-decoration:none;
    font-weight:500;
}

.depoimentos{
    background:#f9f9f9;
}

.depoimento{
    max-width:600px;
    margin:20px auto;
    font-style:italic;
}

footer{
    background:#8B0000;
    color:white;
    padding:30px;
    text-align:center;
}

/* Botão flutuante WhatsApp */
.float{
    position:fixed;
    width:60px;
    height:60px;
    bottom:20px;
    right:20px;
    background:#25D366;
    border-radius:50%;
    display:flex;
    justify-content:center;
    align-items:center;
    color:white;
    font-size:30px;
    text-decoration:none;
}
</style>
</head>

<body>

<header>
    <h1>🐰 Doce Páscoa</h1>
    <nav>
        <a href="#produtos">Produtos</a>
        <a href="#sobre">Sobre</a>
        <a href="#contato">Contato</a>
    </nav>
</header>

<section class="hero">
    <div>
        <h2>Ovos Artesanais que Encantam</h2>
        <a href="#produtos" class="btn">Ver Produtos</a>
    </div>
</section>

<section id="produtos" class="section">
    <h2>Nossos Ovos</h2>
    <div class="produtos">

        <div class="card">
            
            <h3>Ovo Tradicional 500g</h3>
            <div class="preco">R$ 45,00</div>
            <a class="whatsapp-btn" href="https://wa.me/5511992754119?text=Olá,%20quero%20comprar%20o%20Ovo%20Tradicional%20500g">
                Comprar
            </a>
        </div>

        <div class="card">
            
            <h3>Ovo Recheado Premium</h3>
            <div class="preco">R$ 69,00</div>
            <a class="whatsapp-btn" href="https://wa.me/5511973893194?text=Olá,%20quero%20comprar%20o%20Ovo%20Recheado">
                Comprar
            </a>
        </div>

        <div class="card">
           
            <h3>Ovo Infantil com Brinde</h3>
            <div class="preco">R$ 55,00</div>
            <a class="whatsapp-btn" href="https://wa.me/5511918505795?text=Olá,%20quero%20comprar%20o%20Ovo%20Infantil">
                Comprar
            </a>
        </div>

    </div>
</section>

<section id="sobre" class="section">
    <h2>Sobre Nós</h2>
    <p>Somos especialistas em chocolates artesanais, produzidos com ingredientes selecionados e muito carinho. Nossa missão é tornar sua Páscoa ainda mais doce e especial.</p>
</section>

<section class="section depoimentos">
    <h2>O que nossos clientes dizem</h2>
    <div class="depoimento">"Os melhores ovos que já provei! Atendimento impecável."</div>
    <div class="depoimento">"Entrega rápida e chocolate maravilhoso!"</div>
</section>

<section id="contato" class="section">
    <h2>Contato</h2>
    <p>WhatsApp: (00) 00000-0000</p>
    <p>Entregas para sua região</p>
</section>

<footer>
    © 2026 Doce Páscoa - Todos os direitos reservados
</footer>

<a class="float" href="https://wa.me/5500000000000">💬</a>

</body>
</html>
