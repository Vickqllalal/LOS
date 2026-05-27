# LOS 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LOS - Logística na Organização da Saúde</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#f4f9ff;
    overflow-x:hidden;
}

/* HEADER */

header{
    background:#5DA9FF;
    padding:20px 25px;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    flex-wrap:wrap;
}

.logo{
    color:white;
}

.logo h1{
    font-size:48px;
}

.logo p{
    font-size:14px;
}

.menu{
    display:flex;
    gap:25px;
    list-style:none;
    flex-wrap:wrap;
}

.menu a{
    color:white;
    text-decoration:none;
    font-weight:bold;
    font-size:18px;
    transition:0.3s;
}

.menu a:hover{
    color:#dff1ff;
}

/* HERO */

.hero{
    background:#5DA9FF;
    color:white;
    padding:50px 25px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    gap:40px;
    flex-wrap:wrap;
}

.hero-text{
    flex:1;
    min-width:280px;
}

.hero-text h2{
    font-size:60px;
    line-height:1.1;
    margin-bottom:25px;
}

.hero-text p{
    font-size:22px;
    line-height:1.6;
    margin-bottom:35px;
}

.buttons{
    display:flex;
    gap:15px;
    flex-wrap:wrap;
}

.btn{
    padding:18px 28px;
    border:none;
    border-radius:14px;
    cursor:pointer;
    font-size:18px;
    font-weight:bold;
    transition:0.3s;
}

.btn-primary{
    background:#8EC5FF;
    color:white;
}

.btn-secondary{
    background:transparent;
    border:2px solid white;
    color:white;
}

.btn:hover{
    transform:scale(1.05);
}

.hero img{
    width:500px;
    max-width:100%;
    border-radius:30px;
    box-shadow:0 5px 20px rgba(0,0,0,0.2);
}

/* CARDS */

.cards{
    padding:50px 25px;
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    padding:35px 25px;
    border-radius:25px;
    text-align:center;
    box-shadow:0 4px 15px rgba(0,0,0,0.08);
    transition:0.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.icon{
    width:80px;
    height:80px;
    margin:auto;
    border-radius:50%;
    background:#DDEEFF;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:35px;
    color:#5DA9FF;
    margin-bottom:20px;
}

.card h3{
    color:#5DA9FF;
    margin-bottom:15px;
    font-size:30px;
}

.card p{
    font-size:20px;
    line-height:1.5;
}

/* MISSÃO */

.mission{
    padding:70px 25px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    gap:40px;
    flex-wrap:wrap;
}

.mission-text{
    flex:1;
    min-width:280px;
}

.mission-text span{
    color:#5DA9FF;
    font-weight:bold;
    font-size:18px;
}

.mission-text h2{
    font-size:55px;
    margin:20px 0;
    color:#3a6ea5;
    line-height:1.1;
}

.mission-text p{
    font-size:22px;
    line-height:1.6;
    color:#444;
    margin-bottom:30px;
}

.mission img{
    width:500px;
    max-width:100%;
    border-radius:25px;
    box-shadow:0 5px 20px rgba(0,0,0,0.2);
}

/* FOOTER */

footer{
    background:#5DA9FF;
    color:white;
    padding:50px 25px 20px;
}

.footer-content{
    display:flex;
    justify-content:space-between;
    gap:40px;
    flex-wrap:wrap;
}

.footer-box h2{
    font-size:50px;
    margin-bottom:10px;
}

.footer-box h3{
    font-size:28px;
    margin-bottom:15px;
}

.footer-box p,
.footer-box li{
    list-style:none;
    font-size:20px;
    line-height:1.7;
}

.copy{
    margin-top:30px;
    border-top:1px solid rgba(255,255,255,0.3);
    text-align:center;
    padding-top:20px;
    font-size:16px;
}

/* RESPONSIVO */

@media(max-width:768px){

    nav{
        justify-content:center;
        gap:20px;
    }

    .menu{
        justify-content:center;
    }

    .hero{
        text-align:center;
    }

    .hero-text h2{
        font-size:42px;
    }

    .hero-text p{
        font-size:18px;
    }

    .buttons{
        justify-content:center;
    }

    .mission{
        text-align:center;
    }

    .mission-text h2{
        font-size:38px;
    }

    .mission-text p{
        font-size:18px;
    }

    .footer-content{
        justify-content:center;
        text-align:center;
    }

}

</style>
</head>

<body>

<header>

<nav>

<div class="logo">
<h1>LOS</h1>
<p>Logística na Organização da Saúde</p>
</div>

<ul class="menu">
<li><a href="#">Missão</a></li>
<li><a href="#">Visão</a></li>
<li><a href="#">Valores</a></li>
</ul>

</nav>

</header>

<!-- HERO -->

<section class="hero">

<div class="hero-text">

<h2>
Logística de
Medicamentos e
Vacinas
</h2>

<p>
Garantimos qualidade, segurança e eficiência
em toda a cadeia logística, desde o armazenamento
até a distribuição de medicamentos e vacinas.
</p>

<div class="buttons">

<button class="btn btn-primary"
onclick="saibaMais()">
Saiba mais
</button>

<button class="btn btn-secondary"
onclick="mostrarEquipe()">
Equipe
</button>

</div>

</div>

<img src="https://images.unsplash.com/photo-1587854692152-cbe660dbde88?q=80&w=1200&auto=format&fit=crop">

</section>

<!-- CARDS -->

<section class="cards">

<div class="card">
<div class="icon">✓</div>
<h3>Qualidade</h3>

<p>
Garantimos o mais alto padrão
de qualidade em todos os nossos processos.
</p>
</div>

<div class="card">
<div class="icon">🚚</div>
<h3>Eficiência</h3>

<p>
Processos logísticos otimizados
para entregas rápidas e seguras.
</p>
</div>

<div class="card">
<div class="icon">👥</div>
<h3>Compromisso</h3>

<p>
Comprometidos com a saúde
e o bem-estar da população.
</p>
</div>

</section>

<!-- MISSÃO -->

<section class="mission">

<div class="mission-text">

<span>NOSSA MISSÃO</span>

<h2>
Levar saúde com
responsabilidade
e excelência
</h2>

<p>
Atuamos para integrar pessoas, processos
e tecnologia, garantindo que medicamentos
e vacinas cheguem a quem precisa,
com segurança e pontualidade.
</p>

<button class="btn btn-primary"
onclick="mostrarMissao()">
Conheça nossa missão
</button>

</div>

<img src="https://images.unsplash.com/photo-1584017911766-d451b3d0e843?q=80&w=1200&auto=format&fit=crop">

</section>

<!-- FOOTER -->

<footer>

<div class="footer-content">

<div class="footer-box">

<h2>LOS</h2>

<p>Logística na Organização da Saúde</p>

<br>

<p>
Eficiência que transforma,
saúde que conecta.
</p>

</div>

<div class="footer-box">

<h3>Colaboradores</h3>

<ul>
<li>Vitória</li>
<li>Kauan</li>
<li>Isabella</li>
<li>Noemi</li>
</ul>

</div>

</div>

<div class="copy">
© 2025 LOS - Todos os direitos reservados.
</div>

</footer>

<script>

function saibaMais(){
    alert("A LOS oferece logística segura e eficiente para medicamentos e vacinas.");
}

function mostrarEquipe(){
    alert("Colaboradores: Vitória, Kauan, Isabella e Noemi.");
}

function mostrarMissao(){
    alert("Nossa missão é levar saúde com responsabilidade e excelência.");
}

</script>

</body>
</html>
