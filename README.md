<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ONG Jovem Aprendiz</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Inter', sans-serif;
      background-color: #f9fafb;
      color: #111827;
      line-height: 1.6;
    }

    header {
      background: white;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 999;
    }

    header h1 {
      font-size: 24px;
      font-weight: 800;
      color: #00695c;
    }

    nav ul {
      display: flex;
      list-style: none;
      gap: 30px;
    }

    nav ul li a {
      text-decoration: none;
      color: #333;
      font-weight: 500;
      transition: color 0.3s;
    }

    nav ul li a:hover {
      color: #00695c;
    }

    .mari {
      height: 85vh;
      background: linear-gradient(to right, #00695caa, #00695cbb), url('https://conteudo.senacrs.com.br/wp-content/uploads/2023/08/aprendizvetor3.png') center/cover no-repeat;
      display: flex;
      align-items: center;
      justify-content: flex-start;
      padding: 0 80px;
      color: white;
    }

    .mari h2 {
      font-size: 48px;
      max-width: 600px;
      font-weight: 800;
    }

    section {
      padding: 80px 40px;
      max-width: 1200px;
      margin: auto;
    }

    section h2 {
      font-size: 36px;
      text-align: center;
      margin-bottom: 40px;
      font-weight: 700;
    }

    .grid-3 {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }

    .card {
      background: white;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.05);
      text-align: center;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card i {
      font-size: 36px;
      margin-bottom: 15px;
      color: #00695c;
    }

    .cta {
      background: #00695c;
      color: white;
      padding: 80px 40px;
      text-align: center;
    }

    .cta h2 {
      font-size: 36px;
      margin-bottom: 20px;
    }

    .cta p {
      font-size: 18px;
      margin-bottom: 30px;
    }

    .cta button {
      background: #a9ec5b;
      border: none;
      padding: 14px 28px;
      font-size: 16px;
      font-weight: bold;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s;
    }

    .cta button:hover {
      background:#d8fa60;

    
      
    }

    .nanda {
      padding: 80px 40px;
      text-align: center;
    }

    .nanda iframe {
      width: 100%;
      height: 450px;
      border: 0;
      border-radius: 12px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.05);
    }

    footer {
      background: #004d40;
      color: white;
      text-align: center;
      padding: 30px;
      font-size: 14px;
    }

    @media (max-width: 768px) {
      .mari {
        padding: 40px;
        justify-content: center;
        text-align: center;
      }

      .mari h2 {
        font-size: 32px;
      }

      nav ul {
        flex-direction: column;
        gap: 10px;
        margin-top: 10px;
      }
    }

    

       
    
        .timer{
            display: flex;
            justify-content: center;
            color: rgb(10, 61, 35);
            gap: 50px;
            margin-top: 40px;
            font-size: 10pt;
            
        }
        #isa{
            margin-top: 10px;
        }

        .nanda h2{
          color:#111827
        }
        

    
  </style>
</head>
<body>

  <header>
    <h1>ONG Jovem Aprendiz</h1>
    <nav>
      <ul>
        <li><a href="#sobre">Quem Somos</a></li>
        <li><a href="#programas">Programas</a></li>
        <li><a href="#eventos">Eventos</a></li>
        <li><a href="#contato">Contato</a></li>
        <li><a href="#mapa">Localização</a></li>
      </ul>
    </nav>
  </header>

  <div class="mari">
    <h2>Transformamos o futuro de jovens através da educação e do trabalho</h2>
  </div>
  <section id="sobre">
    <h2>Sobre a ONG</h2>
    <div class="grid-3">
      <div class="card">
        <i class="fa-solid fa-eye"></i>
        <h3>Missão</h3>
        <p>Capacitar jovens em situação de vulnerabilidade social, oferecendo oportunidades de aprendizado e inserção no mercado de trabalho.</p>
      </div>
      <div class="card">
        <i class="fa-solid fa-bullseye"></i>
        <h3>Visão</h3>
        <p>Ser referência no Brasil como agente de transformação social por meio da formação profissional e cidadã.</p>
      </div>
      <div class="card">
        <i class="fa-solid fa-chart-line"></i>
        <h3>Impacto</h3>
        <p>Mais de 5 mil jovens formados, com taxa de 78% de inserção no mercado formal de trabalho em 2024.</p>
      </div>
    </div>
  </section>

  <section id="programas">
    <h2>Programas em Destaque</h2>
    <div class="grid-3">
      <div class="card">
        <i class="fa-solid fa-briefcase"></i>
        <h3>Jovem Aprendiz</h3>
        <p>Parcerias com empresas para incluir jovens no mercado de trabalho com formação teórica e prática.</p>
      </div>
      <div class="card">
        <i class="fa-solid fa-laptop-code"></i>
        <h3>Capacitação Tech</h3>
        <p>Cursos gratuitos de informática, design e programação para aumentar a empregabilidade juvenil.</p>
      </div>
      <div class="card">
        <i class="fa-solid fa-comments"></i>
        <h3>Mentoria Profissional</h3>
        <p>Conectamos jovens a mentores voluntários que os orientam na construção de carreira e autoconfiança.</p>
      </div>
    </div>
  </section>
  <section id="novos-cards">
  <h2>Mais Informações</h2>
  <div class="grid-3">
    <div class="card">
      <i class="fa-solid fa-hands-helping"></i>
      <h3>Seja Voluntário</h3>
      <p>Participe das nossas ações e ajude a transformar o futuro de jovens em todo o Brasil.</p>
    </div>
    <div class="card">
      <i class="fa-solid fa-comments-dollar"></i>
      <h3>Transparência</h3>
      <p>Relatórios anuais e dados sobre o uso de recursos estão disponíveis para todos.</p>
    </div>
    <div class="card">
      <i class="fa-solid fa-heart"></i>
      <h3>Depoimentos</h3>
      <p>Confira histórias reais de jovens que mudaram de vida com a nossa ajuda.</p>
    </div>
  </div>
</section>
  <section id="eventos">
    <h2>Próximos Eventos</h2>
   <div class="card">
  <i class="fa-solid fa-calendar-day"></i>
  <h3>Curso de TI - Programação e Desenvolvimento</h3>
        <p><strong>Horário:</strong> Segunda a Sexta</p>
        <p><strong>Dia de Início:</strong> 1º de Julho   <strong>Hora:</strong> 18h às 21h</p>
        <p><strong>Local:</strong> Centro de Capacitação Profissional</p>
        <p><strong>Endereço:</strong> Rua Exemplo, 123, Bairro Centro</p>
    
        <div id="isa"><p><strong>Início em:</strong></p></div>
        
   
    <div class="timer">
        <div>
            <h1 id="dia">00</h1>
            <p>Dias</p>
        </div>
        <div>
            <h1 id="horas">00</h1>
            <p>Horas</p>
        </div>
        <div>
            <h1 id="minutos">00</h1>
            <p>Minutos</p>
        </div>
        <div>
            <h1 id="segundos">00</h1>
            <p>Segundos</p>
        </div>
    </div>
  <div id="contador" class="contador-estilizado"></div>
  
</div>

        
    </div>
  </section>

  <div class="cta" id="contato" style="background-color: #f8f8f8; padding: 60px 20px; text-align: center; font-family: Arial, sans-serif;">
  <h2 style="font-size: 32px; color: #333; margin-bottom: 10px;">Quer ajudar ou participar?</h2>
  <h2 style="font-size: 28px; color: #4CAF50; margin-top: 0;">Entre em Contato</h2>
  
  <p style="color: #666; font-size: 16px; margin-bottom: 40px;">Preencha o formulário abaixo e retornaremos em breve.</p>
<form id="whatsappForm" onsubmit="enviarParaWhatsApp(event)" style="max-width: 600px; margin: 0 auto; background: #fff; padding: 30px; border-radius: 10px; box-shadow: 0 0 20px rgba(0,0,0,0.1);">
  <div style="display: flex; flex-direction: column; gap: 15px;">
    <input type="text" name="nome" placeholder="Nome" required 
           style="padding: 12px; border-radius: 6px; border: 1px solid #ccc; font-size: 16px;">
    
    <input type="email" name="email" placeholder="Email" required 
           style="padding: 12px; border-radius: 6px; border: 1px solid #ccc; font-size: 16px;">
    
    <input type="tel" name="telefone" placeholder="Telefone" 
           style="padding: 12px; border-radius: 6px; border: 1px solid #ccc; font-size: 16px;">
    
    <input type="text" name="assunto" placeholder="Assunto" 
           style="padding: 12px; border-radius: 6px; border: 1px solid #ccc; font-size: 16px;">
    
    <textarea name="mensagem" placeholder="Informe o motivo de seu contato..." rows="5"
              style="padding: 12px; border-radius: 6px; border: 1px solid #ccc; font-size: 16px;"></textarea>

    <button type="submit" 
            style="background-color: #4CAF50; color: white; padding: 14px; border: none; border-radius: 8px; font-size: 16px; font-weight: bold; cursor: pointer; transition: background-color 0.3s;">
      Enviar
    </button>
  </div>
</form>

<script>
  function enviarParaWhatsApp(event) {
    event.preventDefault();

    const form = document.getElementById('whatsappForm');
    const nome = form.nome.value.trim();
    const email = form.email.value.trim();
    const telefone = form.telefone.value.trim();
    const assunto = form.assunto.value.trim();
    const mensagem = form.mensagem.value.trim();

    if (!nome || !email || !mensagem) {
      alert('Por favor, preencha ao menos Nome, Email e Mensagem.');
      return;
    }

    const texto = `Olá! Gostaria de entrar em contato:
*Nome:* ${nome}
*Email:* ${email}
*Telefone:* ${telefone}
*Assunto:* ${assunto}
*Mensagem:* ${mensagem}`;

    const numeroDestino = '556984890246'; // Substitua pelo seu número
    const link = `https://wa.me/${numeroDestino}?text=${encodeURIComponent(texto)}`;

    const confirmar = confirm("Deseja realmente enviar essa mensagem via WhatsApp?");
    if (confirmar) {
      window.open(link, '_blank');
    }
  }
</script>


  <p style="margin-top: 40px; color: #444; font-size: 16px;">Entre em contato conosco para saber como ser voluntário, parceiro ou inscrever um jovem.</p>

  <div style="margin-top: 20px; font-size: 16px; color: #555;">
    <p><strong>Instagram:</strong> 
      <a href="https://www.instagram.com/_marrymmn" target="_blank" style="color: #4CAF50; text-decoration: none;">@_marrymmn</a>
    </p>
    <p><strong>WhatsApp:</strong> 
      <a href="https://wa.me/556992375853" target="_blank" style="color: #4CAF50; text-decoration: none;">(55) 69 9237-5853</a>
    </p>
  </div>

  <button onclick="location.href='https://www.instagram.com/nanda_alaac'" 
          target="_blank" 
          style="margin-top: 30px; background-color: #4CAF50; padding: 12px 24px; border: none; border-radius: 6px; font-size: 16px; font-weight: bold; cursor: pointer;">
    Entrar em Contato
  </button>

 


  <div class="nanda" id="mapa">
    <h2>Localização</h2>
    <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d6149.641854964188!2d-46.60970034750401!3d-23.58284405960228!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1spt-BR!2sbr!4v1747870599359!5m2!1spt-BR!2sbr" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
  </div>

  <footer>
  &copy; 2025 ONG Jovem Aprendiz — Todos os direitos reservados<br>
</footer>



</body>
<script>
        const dia = document.getElementById('dia')
        const horas = document.getElementById('horas')
        const minutos = document.getElementById('minutos')
        const segundos = document.getElementById('segundos')

        const dataFinal = "1 jul 2025"

        function countDown() {
            const dataDeTermino = new Date(dataFinal)
            const hoje = new Date()
            const segTotal = (dataDeTermino - hoje) / 1000

            const finalDias = Math.floor(segTotal / 60 / 60 / 24)
            const finalHoras = Math.floor(segTotal / 60 / 60) % 24
            const finalMinutos = Math.floor(segTotal / 60) % 60
            const finalSegundos = Math.floor(segTotal) % 60

            dia.innerHTML = finalDias
            horas.innerHTML = formatoTempo(finalHoras)
            minutos.innerHTML = formatoTempo(finalMinutos)
            segundos.innerHTML = formatoTempo(finalSegundos)
        }

        function formatoTempo(tempo) {
            return tempo < 10 ? '0' + tempo : tempo;
        }

        countDown()
        setInterval(countDown, 1000)
    </script>
</body>
</html>
</html>
