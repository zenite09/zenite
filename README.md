<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Zênite Marketing Digital</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      scroll-behavior: smooth;
    }
    .hero {
      background: linear-gradient(to right, #000000, #222);
      color: #fff;
      padding: 100px 20px;
      text-align: center;
    }
    .hero h1 {
      font-size: 3rem;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 1.3rem;
    }
    .section-title {
      margin-bottom: 40px;
    }
    .card {
      border: none;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    footer {
      background: #000;
      color: #fff;
      padding: 40px 0;
    }
    .btn-z {
      background-color: #00b894;
      color: white;
      border: none;
    }
    .btn-z:hover {
      background-color: #01906f;
    }
  </style>
</head>
<body>

  <!-- Hero Section -->
  <section class="hero" id="inicio">
    <div class="container">
      <h1>ZÊNITE MARKETING DIGITAL</h1>
      <p>Impulsione sua presença nas redes sociais. Nós gerenciamos. Você cresce.</p>
      <a href="#contato" class="btn btn-z btn-lg mt-4">Vamos Conversar</a>
    </div>
  </section>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
    <div class="container">
      <a class="navbar-brand" href="#">Zênite</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="menu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a href="#sobre" class="nav-link">Sobre</a></li>
          <li class="nav-item"><a href="#servicos" class="nav-link">Serviços</a></li>
          <li class="nav-item"><a href="#portfolio" class="nav-link">Portfólio</a></li>
          <li class="nav-item"><a href="#planos" class="nav-link">Planos</a></li>
          <li class="nav-item"><a href="#contato" class="nav-link">Contato</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Sobre -->
  <section id="sobre" class="py-5">
    <div class="container">
      <h2 class="text-center section-title">Quem Somos</h2>
      <p class="lead text-center">Na Zênite Marketing Digital, transformamos marcas em referência no digital. Oferecemos soluções completas em redes sociais — do planejamento estratégico à criação de conteúdo, design e análise de performance.</p>
    </div>
  </section>

  <!-- Serviços -->
  <section id="servicos" class="py-5 bg-light">
    <div class="container">
      <h2 class="text-center section-title">O que fazemos por você</h2>
      <div class="row g-4">
        <div class="col-md-6 col-lg-3">
          <div class="card h-100 p-3">
            <h5>📲 Gerenciamento de Redes Sociais</h5>
            <p>Planejamento, postagens, design e relatórios sob medida.</p>
          </div>
        </div>
        <div class="col-md-6 col-lg-3">
          <div class="card h-100 p-3">
            <h5>🎨 Conteúdo Estratégico</h5>
            <p>Posts criativos, carrosséis e vídeos curtos que engajam.</p>
          </div>
        </div>
        <div class="col-md-6 col-lg-3">
          <div class="card h-100 p-3">
            <h5>📈 Análise e Relatórios</h5>
            <p>Métricas e otimizações constantes para crescimento real.</p>
          </div>
        </div>
        <div class="col-md-6 col-lg-3">
          <div class="card h-100 p-3">
            <h5>🧠 Consultoria Estratégica</h5>
            <p>Ajuda personalizada para sua empresa crescer no digital.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Portfólio -->
  <section id="portfolio" class="py-5">
    <div class="container">
      <h2 class="text-center section-title">Resultados que falam por si</h2>
      <p class="text-center">Confira alguns dos perfis que transformamos com estratégia, consistência e muito design.</p>
      <!-- Aqui você pode adicionar imagens ou carrossel -->
    </div>
  </section>

  <!-- Planos -->
  <section id="planos" class="py-5 bg-light">
    <div class="container">
      <h2 class="text-center section-title">Nossos Planos</h2>
      <div class="row g-4">
        <div class="col-md-4">
          <div class="card p-4 h-100">
            <h5 class="text-center">Essencial</h5>
            <ul>
              <li>12 postagens/mês</li>
              <li>1 rede social</li>
              <li>Relatório mensal</li>
              <li>Suporte via WhatsApp</li>
            </ul>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card p-4 h-100">
            <h5 class="text-center">Profissional</h5>
            <ul>
              <li>20 postagens/mês</li>
              <li>2 redes sociais</li>
              <li>Stories semanais</li>
              <li>Reunião mensal</li>
            </ul>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card p-4 h-100">
            <h5 class="text-center">Premium</h5>
            <ul>
              <li>30+ postagens/mês</li>
              <li>Até 3 redes sociais</li>
              <li>Stories diários</li>
              <li>Gestão de anúncios</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="text-center mt-4">
        <a href="#contato" class="btn btn-z">Solicite um orçamento</a>
      </div>
    </div>
  </section>

  <!-- Contato -->
  <section id="contato" class="py-5">
    <div class="container">
      <h2 class="text-center section-title">Fale com a gente</h2>
      <div class="row justify-content-center">
        <div class="col-md-8">
          <form>
            <input type="text" class="form-control mb-3" placeholder="Seu nome" required>
            <input type="email" class="form-control mb-3" placeholder="Seu e-mail" required>
            <input type="text" class="form-control mb-3" placeholder="Seu WhatsApp" required>
            <textarea class="form-control mb-3" rows="5" placeholder="Como podemos ajudar?" required></textarea>
            <button type="submit" class="btn btn-z w-100">Enviar</button>
          </form>
          <p class="text-center mt-3">Ou chame direto no WhatsApp: <a href="https://wa.me/55SEUNUMERO" target="_blank">Clique aqui</a></p>
        </div>
      </div>
    </div>
  </section>

  <!-- Rodapé -->
  <footer>
    <div class="container text-center">
      <p>Zênite Marketing Digital © 2025</p>
      <p>Especialistas em redes sociais para empresas e marcas.</p>
      <p>Email: contato@zenitemarketing.com.br</p>
      <p>CNPJ: 00.000.000/0001-00</p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
