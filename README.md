Ju<table>
  <tr>
    <th>Nome</th>
    <th>Idade</th>
    <th>Cidade</th>
  </tr>
  <tr>
    <td>João</td>
    <td>25</td>
    <td>São Paulo</td>
  </tr>
  <tr>
    <td>Maria</td>
    <td>30</td>
    <td>Rio de Janeiro</td>
  </tr>
</table><html>

<html>
<!DOCTYPE html>
<html>
<head>
  <title>Formulário de Dados Pessoais</title>
</head>
<body>
  <h2>Formulário de Dados Pessoais</h2>
  <form>
    <label for="nome">Nome completo:</label><br>
    <input type="text" id="nome" name="nome" required><br><br>

    <label for="idade">Idade:</label><br>
    <input type="number" id="idade" name="idade" required><br><br>

    <label for="email">E-mail:</label><br>
    <input type="email" id="email" name="email" required><br><br>

    <label for="telefone">Telefone:</label><br>
    <input type="tel" id="telefone" name="telefone"><br><br>

    <label for="endereco">Endereço:</label><br>
    <input type="text" id="endereco" name="endereco"><br><br>

    <input type="submit" value="Enviar">
  </form>
</body>
</html>
<html>
<h1>Bem-vindo à pagina</h1>

<h2>Produto</h2>

<img src="HTML//1.jpg" alt="imagem" width="340">

<h2> vídeo</h2>

<video width="400" controls>
  <source src="HTLM//1.mp4" type="video/mp4">
  O seu navegador  suporta vídeo.
</video>
</html>
# Meus-projetos-de-HTML-

<!DOCTYPE html>
<html>
<head>
  <title>Escola</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Escola</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="cadastro-alunos.html">Cadastrar Alunos</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <h2>Bem-vindo à nossa escola!</h2>
    <p>Alunos cadastrados: <span id="alunos-cadastrados">0</span></p>
    <p>Alunos não cadastrados: <span id="alunos-nao-cadastrados">0</span></p>
    <h3>Alunos Cadastrados:</h3>
    <ul id="lista-alunos-cadastrados"></ul>
    <h3>Alunos Não Cadastrados:</h3>
    <ul id="lista-alunos-nao-cadastrados"></ul>
  </main>

  <script>
    let alunosCadastrados = [];
    let alunosNaoCadastrados = [];

    function atualizarDados() {
      document.getElementById('alunos-cadastrados').innerText = alunosCadastrados.length;
      document.getElementById('alunos-nao-cadastrados').innerText = alunosNaoCadastrados.length;
      document.getElementById('lista-alunos-cadastrados').innerHTML = alunosCadastrados.map(aluno => `<li>${aluno.nome} - ${aluno.idade} anos</li>`).join('');
      document.getElementById('lista-alunos-nao-cadastrados').innerHTML = alunosNaoCadastrados.map(aluno => `<li>${aluno.nome} - ${aluno.idade} anos</li>`).join('');
    }

    // Simulação de dados
    alunosCadastrados = [
      { nome: 'João', idade: 15 },
      { nome: 'Maria', idade: 16 }
    ];
    alunosNaoCadastrados = [
      { nome: 'Pedro', idade: 17 },
      { nome: 'Ana', idade: 18 }
    ];
    atualizarDados();
  </script>
</body>
</html>

<table border="1">
  <tr>
    <th>Nome</th>
    <th>Idade</th>
    <th>Cidade</th>
  </tr>
  <tr>
    <td>Augusto</td>
    <td>25</td>
    <td>São Paulo</td>
  </tr>
  <tr>
    <td>Zamba</td>
    <td>20</td>
    <td>Rio de Janeiro</td>
  </tr>
</table>
<form action="" method="post">
  <label for="nome">Nome:</label>
  <input type="text" id="nome" name="nome"><br><br>

  <label for="sobrenome">Sobrenome:</label>
  <input type="text" id="sobrenome" name="sobrenome"><br><br>

  <label for="email">E-mail:</label>
  <input type="email" id="email" name="email"><br><br>

  <label for="senha">Senha:</label>
  <input type="password" id="senha" name="senha"><br><br>

  <label for="genero">Gênero:</label>
  <select id="genero" name="genero">
    <option value="masculino">Masculino</option>
    <option value="feminino">Feminino</option>
    <option value="outro">Outro</option>
  </select><br><br>

  <label for="termos">Aceito os termos e condições:</label>
  <input type="checkbox" id="termos" name="termos"><br><br>

  <input type="submit" value="Enviar">
</form>
<!DOCTYPE html>
<html>
<head>
  <title>Projeto Multimídia</title>
</head>
<body>
  <h1>Projeto Multimídia</h1>

  <h2>Áudio:</h2>
  <audio controls>
    <source src=AUD-20251123-WA0051".mp3" type="audio/mp3">
  </audio>

  <h2>Vídeo:</h2>
  <video width="230" height="230" controls>
    <source src="VID_20251121_194230.mp4" type="video/00:30mp4">
  </video>

  <h2>Foto:</h2>
  <img src="+244 926 542 005 20250925_224315(0)/+244 926 542 005 20250925_224315(0)" alt="minha foto" width="200">

</body>
</html>

<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <title>Agência de Viagens</title>
  <style>
    body { font-family: Arial; background: #f0f0f0; padding: 20px; }
    header { background: #0099cc; color: white; padding: 15px; text-align: center; }
    section { background: white; padding: 20px; margin-top: 10px; border-radius: 8px; }
    footer { text-align: center; margin-top: 20px; color: #666; }
  </style>
</head>
<body>
  <header>
    <h1>Bem-vindo à Viagem dos Sonhos</h1>
    <p>Descubra destinos incríveis com os melhores preços!</p>
  </header>

  <section>
    <h2>Destinos Populares</h2>
    <ul>
      <li>Praias de Moçambique</li>
      <li>Luanda - Ilha do Cabo</li>
      <li>Lisboa, Portugal</li>
      <li>Dubai, Emirados Árabes</li>
      <li>Angola,Luanda</li>
  
    </ul>
  </section>

  <section>
    <h2>Reservar uma viagem</h2>
    <form>
      Nome: <input type="text" name="nome"><br><br>
      E-mail: <input type="email" name="email"><br><br>
      Destino: <input type="text" name="destino"><br><br>
      <button type="submit">Reservar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2030 Viagem dos Sonhos</p>
  </footer>
</body>
</html>


