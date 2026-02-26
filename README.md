<html lang="pt">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Caminhada Quaresmal</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Raleway:wght@300;400;500&display=swap" rel="stylesheet">

<style>
    /* Reset básico para garantir consistência */
    * { margin: 0; padding: 0; box-sizing: border-box; }

    /* Estilo do Fundo Geral - Gradiente Roxo Suave */
    body {
        font-family: 'Raleway', sans-serif;
        background: linear-gradient(135deg, #EEEAF5 0%, #D6CADD 100%); /* Roxo litúrgico muito suave */
        color: #3E2F5B; /* Cor de texto principal: Roxo carvão */
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 100vh;
        padding: 20px;
    }

    /* O Cartão "Flutuante" */
    .card-container {
        background-color: rgba(255, 255, 255, 0.96); /* Branco quase opaco */
        width: 100%;
        max-width: 500px; /* Largura ideal para um flyer tipo A5 */
        padding: 40px;
        border-radius: 20px; /* Cantos arredondados suaves */
        box-shadow: 0 10px 30px rgba(62, 47, 91, 0.15); /* Sombra suave para dar profundidade */
        text-align: center;
        border-top: 4px solid #7A5493; /* Um toque de cor no topo */
    }

/* Estilo para o Logotipo */
    .logo {
        max-width: 100px; /* Tamanho do logotipo */
        height: auto;
        margin: 0 auto 20px auto;
        display: block;
    }


    /* Tipografia e Hierarquia */
    .top-header {
        font-size: 0.75rem;
        text-transform: uppercase;
        letter-spacing: 2px;
        color: #7A5493; /* Cor de destaque ametista */
        font-weight: 600;
        margin-bottom: 15px;
    }

    h1.main-title {
        font-family: 'Playfair Display', serif;
        font-size: 2rem;
        font-weight: 600;
        margin-bottom: 5px;
        line-height: 1.2;
    }

    h2.subtitle {
        font-family: 'Playfair Display', serif;
        font-size: 1.1rem;
        font-weight: 400;
        margin-bottom: 20px;
        color: #5E4B7F;
    }

    /* Caixa de Tema */
    .theme-box {
        background-color: #F4F0F9; /* Fundo roxo muito claro */
        padding: 15px;
        border-radius: 10px;
        margin-bottom: 25px;
        font-weight: 500;
    }

	 /* Caixa de Tema */
    .theme-box-2 {
        background-color: #F4F0F9; /* Fundo roxo muito claro */
        padding: 15px;
        border-radius: 10px;
        margin-bottom: 25px;
        font-weight: 500;

	}	

    /* Separador elegante */
    .separator {
        height: 1px;
        width: 60px;
        background-color: #D6CADD;
        margin: 25px auto;
    }

    /* Chave Espiritual */
    .spiritual-key {
        font-family: 'Playfair Display', serif;
        font-style: regular;
        font-size: 1.1rem;
        line-height: 1.6;
        color: #5E4B7F;
        margin-bottom: 30px;
    }

    /* Secções de Ação */
    .action-section {
        text-align: left;
        margin-top: 30px;
    }

    .section-title {
        font-size: 0.9rem;
        text-transform: uppercase;
        letter-spacing: 1.5px;
        color: #7A5493;
        font-weight: 600;
        margin-bottom: 15px;
        display: flex;
        align-items: center;
    }

    /* Ícones simples usando CSS (círculos) */
    .icon-dot {
        display: inline-block;
        width: 12px;
        height: 12px;
        background-color: #7A5493;
        border-radius: 50%;
        margin-right: 10px;
    }

    /* Listas */
    ul {
        list-style-type: none;
        padding-left: 10px;
    }

    ul li {
        margin-bottom: 12px;
        line-height: 1.5;
        position: relative;
        padding-left: 20px;
    }
    
    ul li::before {
        content: "•";
        color: #7A5493;
        position: absolute;
        left: 0;
        font-size: 1.2em;
    }

    /* Ajustes para impressão */
    @media print {
        body {
            background: none;
            padding: 0;
        }
        .card-container {
            box-shadow: none;
            border-radius: 0;
            max-width: 100%;
            padding: 30px;
            border-top: none; /* Remover a borda superior na impressão se preferir mais limpo */
        }
        /* Garante que as cores de fundo sejam impressas (depende da configuração do navegador também) */
        * {
            -webkit-print-color-adjust: exact;
            print-color-adjust: exact;
        }
    }
</style>
</head>
<body>

    <div class="card-container">
        <img src="https://i.ibb.co/kr304nN/logo-UP-sta-Maria-11.jpg" alt="Logotipo" class="logo">
	<div class="top-header">
            Quaresma 2026 - Do Deserto à Vida
        </div>

        <h2 class="subtitle">Caminhada Quaresmal em Família</h2>

        <div class="theme-box">
            Desafios | Gestos concretos em Família | Sinais Visíveis | Compromissos e renúncias
        </div>

        <div class="separator"></div>

        <div class="spiritual-key">
            Ao longo desta Quaresma, vamos caminhando do Deserto à Vida e aprofundando a nossa espiritualidade através de desafios simples, compromissos individuais e familiares, que nos conduzam a uma verdadeira conversão interior e receonversão das nossas relações uns com os outros e, sobretudo, ganhando cada vez mais intimidade com o Senhor.<br><br>
            Votos de uma Santa Quaresma!
        </div>
		<div class="theme-box-2">
        <a href="https://upsantamaria.github.io/quaresma/semana_1.html">I Semana</a><&nbsp><a href="https://upsantamaria.github.io/quaresma/semana_2.hml">Semana II</a><&nbsp><a href="https://upsantamaria.github.io/quaresma/semana_3.hml">Semana III</a><&nbsp><a href="https://upsantamaria.github.io/quaresma/semana_4.hml">Semana IV</a><&nbsp><a href="https://upsantamaria.github.io/quaresma/semana_5.hml">Semana V</a>
        </div>

    </div>

</body>
</html>
