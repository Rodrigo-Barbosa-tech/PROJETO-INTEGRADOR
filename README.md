**APRENSENTAÇÃO**
  Este projeto consiste em um jogo da velha interativo que permite partidas entre dois jogadores ou entre um jogador e uma inteligência artificial (IA). A aplicação registra as estatísticas de cada partida em um banco de dados, incluindo os nomes dos jogadores, o resultado e a data do jogo. Com foco em proporcionar uma experiência estratégica e envolvente, o jogo foi desenvolvido com tecnologias web modernas e implementado para ser acessível online.
  
**TECNOLOGIAS UTILIZADAS**
  Para a construção e desenvolvimento do projeto, foram empregadas as seguintes tecnologias:

**Front-end:**
  HTML: Define a estrutura da interface. CSS: Responsável pela estilização da interface. JavaScript: Implementa a lógica do jogo e as interações com o usuário.

**Back-end:**
  Node.js: Gerencia a API e a comunicação com o banco de dados.

**Banco de Dados:**
  MySQL: Armazena os dados das partidas, como resultados e jogadores.

**Deploy e Hospedagem :**
  Render: Plataforma utilizada para disponibilizar a aplicação online.

**OBJETIVO**
  Criar uma aplicação web que combina interatividade e inteligência artificial em um jogo da velha, permitindo partidas entre dois jogadores ou contra uma IA. Além de oferecer uma experiência estratégica e envolvente, a aplicação registra os resultados das partidas em um banco de dados para análise e consulta futura. O projeto visa disponibilizar a aplicação de forma acessível, utilizando tecnologias modernas e hospedagem em nuvem.

**FUNCIONALIDADES**

**Interface Simples:**
  Interface intuitiva e de fácil uso, desenvolvida com HTML, CSS e JavaScript.

**Modos de Jogo:**
  -Multiplayer Local: Dois jogadores podem competir no mesmo dispositivo, alternando turnos.
  -Contra Inteligência Artificial: O jogador enfrenta uma IA capaz de realizar jogadas estratégicas.
  
**Sistema de Resultados:**
  -Exibição dos resultados em tempo real durante e após as partidas.
  -Histórico de partidas armazenado no banco de dados, permitindo visualização de vitórias, derrotas e empates.

**Conexão com Banco de Dados:**
  Armazenamento das estatísticas das partidas em um banco de dados MySQL, garantindo persistência das informações e consulta futura.

**Acessibilidade Online:**
  Disponível via navegador em qualquer dispositivo conectado à internet, graças ao deploy em infraestrutura de nuvem.

**REQUISITOS E DEPENDÊNCIAS PARA INSTALAÇÃO**

**Pré-requisitos**

Node.js: Certifique-se de ter o Node.js instalado na máquina. (Pode ser baixado em Node.js).
Banco de Dados MySQL: É necessário baixar e configurar o banco de dados MySQL com credenciais disponibilizadas para acesso(Pode ser baixado em Mysql):
                                                           **Credenciais utilizadas**
(Host:mysql-aula.cuebxlhckhcy.us-east-1.rds.amazonaws.com, Usuário:mysqlaula, Senha:MySQLAula123!, Banco de Dados:mysqlaula, Porta para acesso:3306.)

**DEPENDÊNCIAS DO PROJETO**

Dentro do projeto foram utilizadas as seguintes dependências: Body-parser: Middleware que analisa o corpo das requisições HTTP, como JSON ou URL-encoded, facilitando o acesso aos dados enviados pelo cliente. 
Cors: Middleware que permite o compartilhamento de recursos entre diferentes origens (CORS), habilitando o acesso de domínios externos ao seu servidor. 
Dotenv: Carrega variáveis de ambiente de um arquivo .env, permitindo a configuração segura e flexível de credenciais e variáveis no ambiente de desenvolvimento. 
Express: Framework minimalista para Node.js que facilita a criação de servidores web e APIs, com suporte a roteamento e middleware. 
Mysql2:Biblioteca para conectar e interagir com bancos de dados MySQL, oferecendo uma API rápida e suporte a Promises para facilitar a execução de consultas.
Nodemon:Ferramenta que monitora mudanças no código e reinicia automaticamente o servidor durante o desenvolvimento, evitando a necessidade de reiniciar manualmente o processo.

**COMO RODAR A APLICAÇÃO**
  Para Rodar a aplicação você deve: Primeiro passo instalar o arquivo do repositório e o extrair em sua área de trabalho, em seguida instale o Node.js e o Mysql, configure o Mysql para fazer conexão com o banco de dados da aplicação
com as credenciais disponibilizadas em (Pré requisitos), com o arquivo aberto no vscode abra um terminal e digite npm install, isso fara a instalação das dependências citadas acima que estão localizadas dentro do package.json, após
este processo com o banco de dados já conectado e a aplicação rodando abra o server de hospedagem render (https://jogodavelha-jpju.onrender.com/) por lá poderá utilizar a aplicação em tempo real podendo conferir o armazenamento dos dados, e ainda, 
realizar alterações no código podendo visualizar diretamente na aplicação que foi subida por deploy.
