# LOS
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>LOS - Logística na Organização da Saúde</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body{
    background:#f5f7fb;
    overflow-x:hidden;
}

/* MENU */

header{
    background:#003d99;
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
    font-weight:bold;
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
    color:#73a7ff;
}

/* HERO */

.hero{
    background:#003d99;
    color:white;
    padding:50px 25px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:40px;
    flex-wrap:wrap;
}

.hero-text{
    flex:1;
    min-width:280px;
}

.hero-text h2{
    font-size:62px;
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
    border-radius:14px;
    border:none;
    font-size:18px;
    font-weight:bold;
    cursor:pointer;
    transition:0.3s;
}

.btn-primary{
    background:#2f80ff;
    color:white;
}

.btn-secondary{
    background:transparent;
    border:2px solid white;
    color:white;
}

.btn:hover{
    transform:scale(1.05);
    opacity:0.9;
}

.hero img{
    width:480px;
    max-width:100%;
    border-radius:30px;
}

/* CARDS */

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
    padding:50px 25px;
}

.card{
    background:white;
    padding:35px 25px;
    border-radius:22px;
    text-align:center;
    box-shadow:0 3px 15px rgba(0,0,0,0.08);
    transition:0.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.icon{
    width:80px;
    height:80px;
    background:#edf4ff;
    border-radius:50%;
    display:flex;
    align-items:center;
    justify-content:center;
    margin:0 auto 20px;
    font-size:35px;
    color:#0050cc;
}

.card h3{
    font-size:30px;
    margin-bottom:15px;
    color:#0b2f6d;
}

.card p{
    font-size:20px;
    line-height:1.5;
}

/* MISSÃO */

.mission{
    padding:70px 25px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:40px;
    flex-wrap:wrap;
}

.mission-text{
    flex:1;
    min-width:280px;
}

.mission-text span{
    color:#0050cc;
    font-weight:bold;
    font-size:18px;
}

.mission-text h2{
    font-size:55px;
    color:#0b2f6d;
    margin:18px 0;
    line-height:1.1;
}

.mission-text p{
    font-size:22px;
    line-height:1.6;
    margin-bottom:30px;
    color:#333;
}

.mission img{
    width:500px;
    max-width:100%;
    border-radius:25px;
}

/* FOOTER */

footer{
    background:#003d99;
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
    margin-bottom:15px;
    font-size:28px;
}

.footer-box p,
.footer-box li{
    font-size:20px;
    line-height:1.7;
    list-style:none;
}

.footer-box ul{
    padding:0;
}

.copy{
    text-align:center;
    border-top:1px solid rgba(255,255,255,0.3);
    margin-top:30px;
    padding-top:20px;
    font-size:16px;
}

/* CELULAR */

@media(max-width:768px){

    .hero{
        text-align:center;
    }

    nav{
        justify-content:center;
        gap:20px;
    }

    .menu{
        justify-content:center;
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
        text-align:center;
        justify-content:center;
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
em toda a cadeia logística, desde o
armazenamento até a distribuição de
medicamentos e vacinas.
</p>

<div class="buttons">

<button class="btn btn-primary"
onclick="mostrarMensagem()">
Saiba mais
</button>

<button class="btn btn-secondary"
onclick="falarEquipe()">
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
onclick="missao()">
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

function mostrarMensagem(){
    alert("A LOS garante logística segura para medicamentos e vacinas.");
}

function falarEquipe(){
    alert("Equipe: Vitória, Kauan, Isabella e Noemi.");
}

function missao(){
    alert("Nossa missão é levar saúde com responsabilidade e excelência.");
}

</script>

</body>
</html>
