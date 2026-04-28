<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ganhar Dinheiro Online</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">

<style>
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: #0d0d0d;
    color: #fff;
}

h1,h2 {
    color: red;
}

/* CAPA */
.header {
    height: 100vh;
    background: url('https://images.unsplash.com/photo-1556745757-8d76bdb6984b') center/cover;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.btn {
    background: red;
    padding: 15px 30px;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

/* SEÇÃO */
.section {
    padding: 60px 20px;
    text-align: center;
}

/* DEPOIMENTOS */
.testimonial {
    background: #1a1a1a;
    margin: 10px;
    padding: 20px;
    border-radius: 10px;
}

/* PREÇO */
.price {
    font-size: 40px;
    color: lime;
}

/* WHATS */
.whatsapp {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: green;
    padding: 15px;
    border-radius: 50%;
    font-size: 20px;
}
</style>
</head>

<body>

<!-- CAPA -->
<div class="header">
    <div>
        <h1>Ganhe Dinheiro Online</h1>
        <p>Método simples mesmo começando do zero</p>
        <a href="#oferta" class="btn">QUERO COMEÇAR</a>
    </div>
</div>

<!-- EXPLICAÇÃO -->
<div class="section">
    <h2>O que você vai aprender</h2>
    <p>Aprenda como ganhar dinheiro usando apenas seu celular com métodos testados.</p>
</div>

<!-- BENEFÍCIOS -->
<div class="section">
    <h2>Benefícios</h2>
    <p>✔ Sem precisar aparecer<br>
       ✔ Pode começar hoje<br>
       ✔ Funciona para iniciantes</p>
</div>

<!-- DEPOIMENTOS -->
<div class="section">
    <h2>Resultados de alunos</h2>

    <div class="testimonial">"Ganhei meus primeiros R$200 online!"</div>
    <div class="testimonial">"Nunca imaginei que funcionava!"</div>
</div>

<!-- OFERTA -->
<div id="oferta" class="section">
    <h2>Oferta Especial</h2>
    <p class="price">R$ 29,90</p>
    <p>Acesso imediato ao método completo</p>

    <!-- BOTÃO PAGAMENTO -->
    <a href="#" class="btn">COMPRAR AGORA</a>
</div>

<!-- CAPTURA -->
<div class="section">
    <h2>Ou receba grátis</h2>
    <form onsubmit="salvarLead(event)">
        <input type="text" placeholder="Seu nome" required>
        <input type="email" placeholder="Seu email" required>
        <br><br>
        <button class="btn">Receber dicas</button>
    </form>
</div>

<!-- WHATSAPP -->
<a href="https://wa.me/5511999999999?text=Quero%20aprender%20a%20ganhar%20dinheiro" class="whatsapp">💬</a>

<script>
function salvarLead(e){
    e.preventDefault();
    alert("Cadastro realizado! (integre com backend depois)");
}
</script>

</body>
</html>
