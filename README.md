<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>50 Receitas Fitness Deliciosas e Saudáveis - eBook</title>
<style>
  /* Reset básico */
  * {
    margin: 0; padding: 0; box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
  body {
    background: #f9fdf9;
    color: #333;
    line-height: 1.6;
  }
  a {
    text-decoration: none;
    color: inherit;
  }

  /* Container geral */
  .container {
    max-width: 1000px;
    margin: 0 auto;
    padding: 20px;
  }

  /* Cabeçalho / banner */
  header {
    background: linear-gradient(90deg, #4CAF50, #388E3C);
    color: #fff;
    padding: 60px 20px;
    text-align: center;
    border-radius: 8px;
  }
  header h1 {
    font-size: 2.8rem;
    margin-bottom: 10px;
    font-weight: 700;
  }
  header p {
    font-size: 1.3rem;
    font-weight: 500;
  }

  /* Seções */
  section {
    margin: 40px 0;
    padding: 0 10px;
  }
  section h2 {
    color: #4CAF50;
    margin-bottom: 20px;
    font-size: 2rem;
    border-bottom: 3px solid #4CAF50;
    display: inline-block;
    padding-bottom: 5px;
  }
  section p, section ul {
    font-size: 1.1rem;
    margin-bottom: 15px;
  }
  ul {
    list-style: inside disc;
    color: #555;
  }
  ul li {
    margin-bottom: 8px;
  }

  /* Botão CTA */
  .btn-cta {
    display: inline-block;
    background-color: #FF7043;
    color: #fff;
    font-weight: 700;
    font-size: 1.3rem;
    padding: 15px 40px;
    border-radius: 40px;
    cursor: pointer;
    transition: background-color 0.3s ease;
    border: none;
    margin-top: 15px;
    text-align: center;
  }
  .btn-cta:hover {
    background-color: #E64A19;
  }

  /* Depoimentos */
  .depoimentos {
    display: grid;
    gap: 20px;
    grid-template-columns: repeat(auto-fit,minmax(280px,1fr));
  }
  .depoimento {
    background: #e8f5e9;
    border-left: 6px solid #4CAF50;
    padding: 20px;
    border-radius: 8px;
    font-style: italic;
    color: #2e7d32;
  }
  .depoimento p {
    margin-bottom: 12px;
  }
  .depoimento cite {
    display: block;
    font-style: normal;
    font-weight: 700;
    color: #1b5e20;
    text-align: right;
  }

  /* Oferta e garantia */
  .oferta {
    background: #fff3e0;
    border: 2px solid #FF7043;
    padding: 25px;
    border-radius: 10px;
    text-align: center;
  }
  .oferta strong {
    font-size: 1.5rem;
    color: #D84315;
  }
  .oferta p {
    font-size: 1.2rem;
    margin: 12px 0;
  }
  .garantia {
    margin-top: 30px;
    font-size: 1rem;
    color: #555;
    font-style: italic;
  }

  /* Rodapé */
  footer {
    text-align: center;
    padding: 25px 10px;
    font-size: 0.9rem;
    color: #777;
    border-top: 1px solid #ddd;
  }

  /* Responsividade */
  @media (max-width: 600px) {
    header h1 {
      font-size: 2rem;
    }
    section h2 {
      font-size: 1.5rem;
    }
    .btn-cta {
      width: 100%;
      padding: 15px 0;
    }
  }
</style>
</head>
<body>

<div class="container">

  <header>
    <h1>Transforme sua Alimentação com 50 Receitas Fitness Deliciosas e Saudáveis!</h1>
    <p>Receitas fáceis, rápidas e nutritivas para quem quer emagrecer, ganhar massa magra e ter mais disposição.</p>
  </header>

  <section>
    <h2>O que você vai encontrar aqui?</h2>
    <ul>
      <li>50 receitas completas e originais, testadas e aprovadas</li>
      <li>Ingredientes naturais e acessíveis</li>
      <li>Modo de preparo simples e prático</li>
      <li>Opções variadas de proteínas para adaptar à sua dieta</li>
      <li>Informações nutricionais para controle total</li>
      <li>Perfeito para iniciantes e quem busca mais saúde no dia a dia</li>
    </ul>
  </section>

  <section>
    <h2>Benefícios que você terá</h2>
    <ul>
      <li>Alimentação saborosa sem complicação</li>
      <li>Pratos que ajudam a perder gordura e ganhar músculos</li>
      <li>Economize tempo na cozinha com receitas rápidas</li>
      <li>Controle nutricional para seus objetivos</li>
      <li>Variedade para não enjoar da dieta</li>
    </ul>
  </section>

  <section>
    <h2>Depoimentos</h2>
    <div class="depoimentos">
      <div class="depoimento">
        <p>“Eu nunca achei que comida fitness pudesse ser tão gostosa! Esse eBook mudou minha rotina.”</p>
        <cite>— Ana P.</cite>
      </div>
      <div class="depoimento">
        <p>“Receitas práticas e nutritivas que me ajudaram a emagrecer 7kg em 2 meses.”</p>
        <cite>— Carlos M.</cite>
      </div>
    </div>
  </section>

  <section class="oferta">
    <p><strong>Preço Especial de Lançamento: R$ 37,00</strong></p>
    <p><strong>+ Bônus exclusivo:</strong></p>
    <p>Guia rápido de trocas de proteínas<br />Calendário simples para organizar suas refeições</p>
    <button class="btn-cta" onclick="alert('Parabéns! Você clicou para comprar o eBook.');">QUERO MEU EBOOK AGORA!</button>
    <p class="garantia">Garantia de satisfação 7 dias - Se não gostar do conteúdo, devolvemos seu dinheiro sem complicações.</p>
  </section>

</div>

<footer>
  <p>Contato | Política de Privacidade | Termos de Uso</p>
</footer>

</body>
</html># ebookvendas
