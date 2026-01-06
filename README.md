# Oliveira-Hub
Um site em desenvolvimento 
<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Oliveira Hub | Cursos Online</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }
    body { background: #f4f6f8; color: #333; }
    header {
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #fff; padding: 40px 20px; text-align: center;
    }
    header h1 { font-size: 2.2rem; }
    header p { margin-top: 10px; font-size: 1.1rem; }
    section { padding: 40px 20px; max-width: 1100px; margin: auto; }
    .courses { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .card {
      background: #fff; border-radius: 10px; padding: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.08);
    }
    .card h3 { margin-bottom: 10px; }
    .card p { font-size: 0.95rem; margin-bottom: 15px; }
    .btn {
      display: inline-block; padding: 10px 18px; background: #2c5364;
      color: #fff; text-decoration: none; border-radius: 6px;
    }
    .btn:hover { background: #203a43; }
    footer {
      text-align: center; padding: 20px; background: #0f2027; color: #fff;
    }
    @media (max-width: 600px) {
      header h1 { font-size: 1.8rem; }
    }
  </style>
</head>
<body>  <header>
    <h1>Oliveira Hub</h1>
    <p>Seu centro de cursos online para foco, produtividade e crescimento</p>
  </header>  <section>
    <h2 style="margin-bottom:20px;">📚 Cursos Disponíveis</h2>
    <div class="courses">
      <div class="card">
        <h3>Foco Completo</h3>
        <p>Aprenda técnicas práticas para acabar com a distração e manter o foco total.</p>
        <a href="#" class="btn">Ver curso</a>
      </div>
      <div class="card">
        <h3>Produtividade Máxima</h3>
        <p>Organize sua rotina e produza mais sem estresse.</p>
        <a href="#" class="btn">Ver curso</a>
      </div>
      <div class="card">
        <h3>Disciplina Diária</h3>
        <p>Construa hábitos fortes e consistentes para o dia a dia.</p>
        <a href="#" class="btn">Ver curso</a>
      </div>
    </div>
  </section>  <footer>
    <p>© 2026 Oliveira Hub - Todos os direitos reservados</p>
  </footer></body>
</html>
