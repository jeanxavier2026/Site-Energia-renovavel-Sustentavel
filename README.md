<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Criação de um Projeto Sustentável</title>
    <link rel="stylesheet" href="exemplo fase2.css">
</head>
<body>

    <!-- CABEÇALHO E MENU DE NAVEGAÇÃO -->
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#metas">Metas</a></li>
                <li><a href="#solucoes">Soluções</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

        <!-- SECÇÃO 1: HOME -->
    <section id="home">
        
        <!-- Caixa de texto reposicionada sobre a imagem -->
        <div class="container-home">
            <h2>Energias Renováveis e Acessíveis</h2>
            <p>Garantir o acesso a fontes de energia fiáveis, sustentáveis e modernas para todos.</p>
        </div>
    </section>


        <!-- SECÇÃO 2: METAS -->
    <section id="metas">
        <div class="container">
            <!-- Título da secção com a caixinha de cor leve -->
            
            <h2>Metas do ERS</h2> <!--titulo metas-->
            <span class="badge-titulo">Metas Globais</span><br><br> 

             <!-- Assunto organizado em parágrafos bonitos -->
             <p class="texto-assunto">
                Até 2030, a Agenda do Desenvolvimento Sustentável da ONU estabelece metas globais claras para transformar a nossa matriz energética. O foco está em garantir que nenhuma comunidade fique para trás na transição para um futuro mais limpo.
             </p>
            
             <p class="texto-assunto">
                Para alcançar este objetivo, foram definidos indicadores rigorosos que avaliam o progresso de cada país no acesso universal a serviços modernos, no aumento da eficiência energética e no investimento em infraestruturas sustentáveis.
             </p><br>

             <!-- Lista de Metas do ERA -->
             <ul class="lista-metas">
                <strong>Meta 1</strong> Assegurar o acesso universal a serviços de energia modernos, fiáveis e a preços acessíveis.</li>
              <br><br>  <strong>Meta 2:</strong> Aumentar substancialmente a participação de energias renováveis na matriz energética global.</li>
              <br><br> <strong>Meta 3:</strong> Duplicar a taxa global de melhoria da eficiência energética em vários setores.</li>
            </ul>
        </div>
    </section>
    
      
    <section id="solucoes">
        <div class="container">
            <!-- Título da secção com a caixinha de cor leve -->
            
            <h2>Uma Solução Sustentável...</h2>
            <span class="badge-titulo">Soluções Globais</span><br><br>
            
            <!-- Assunto organizado em parágrafos bonitos -->
            <p class="texto-assunto">
                Aqui serão listadas as tecnologias e projetos práticos de energia limpa (Ex: Energia Solar, Eólica, Hídrica).
    Poderá incluir cartões explicativos ou exemplos práticos em Portugal.</p><br><br>
            
            <h2>Soluções Sustentáveis</h2>

            <!--  -->
            <ul class="lista-metas">
                <strong></strong>Conheça as alternativas: painéis fotovoltaicos, parques eólicos e hidrogénio verde.</p>
        </ul>
        </div>
    </section>

     <!-- SECÇÃO DE CONTACTO (FORMULÁRIO EXIGIDO) -->
     <section id="contacto">
         <div class="container">
             <h2>Entre em Contacto</h2>
             

                 <!-- E mude a propriedade action para ficar assim: -->
                 <form action="sucesso.html" method="POST">

                 <div class="form-group">
                    <input type="text" id="nome" name="nome" placeholder=" " required>
                    <label for="nome">Nome Completo</label>
                 </div>
                 <div class="form-group">
                    <input type="email" id="email" name="email" placeholder=" " required>
                    <label for="email">E-mail</label>
                 </div>
                 <div class="form-group">
                    <textarea id="mensagem" name="mensagem" placeholder=" " required></textarea>
                    <label for="mensagem">A sua Mensagem</label>
                </div>
                <button type="submit">Enviar Requerimento</button>
            </form>
        </div>
    </section>

    <!-- RODAPÉ -->
    <footer>
        <p>&copy; 2026 Criação de um Projeto Sustentável. Links do Projeto: 
            <a href="#home">Descrição</a> | 
            <a href="#contacto">Lista de Funcionalidades</a>  
            <p > &nbsp; |  Desenvolvido por Jean Xavier Aprendiz</p>
        </p>
    </footer>

</body>
</html>
