<p align="center">
  <a href="#Projeto">Projeto</a> ◦ 
  <a href="#Status">Status</a> ◦ 
  <a href="#Sobre">Sobre</a> ◦ 
  <a href="#Funcionalidades">Funcionalidades</a> ◦ 
  <a href="#Tecnologias">Tecnologias</a> ◦ 
  <a href="#Link">Link</a> ◦ 
  <a href="#Autor">Autor</a>
</p>

# Projeto
Calculadora

# Status
Finalizado

# Sobre
Aplicação da Web desenvolvida com a finalidade de aprendizagem dos conteúdos de HTML5, CSS e JavaScript. 
O HTML da página é organizado da seguinte forma:
- head:
    - adiciona o título;
    - relaciona o arquivo de css chamado "style.css", que faz as configurações dos estilos.
- body
    - uma tag section;
    - uma tag table para adicionar todos os botões da calculadora;
    - os botões foram adicionados em seis linhas;
    - ao final faz a relação com o arquivo em JavaScript chamado "main.js".

O documento "main.js" possui as seguintes instruções:  
    - foi optado por adicionar todos os comandos em uma única função, que retorna um objeto com todas as instruções;  
    - o display da calculadora é selecionado com "document.querySelector";  
    - o método que chama todos os demais é "inicia()";  
    - o método "cliqueBotoes()" observa o evento de novos cliques através de "document.addEventListener";  
    - os cliques são classificados utilizando a classe dos botões e para cada clique, um evento diferente é chamado;  
    - o método "clearDisplay()" limpa a tela do display;  
    - o método "apagaUm()" apaga o último digito do display;  
    - o método "realizaConta()" executa o cálculo matemático através do método "eval";  
    - o método "pressionaEnter()" avalia se a tecla "enter" ou "esc" foi pressionada e chama os eventos associados;  
    - o método "btnParaDisplay()" não deixa repetir os caracters "/", "*", "+", "-" e envia os cliques para o display;  
    - ao final, é instanciada a função "criaCalculadora()" e chamado o método "calculadora.inicia()".

# Funcionalidades
- [x] Display para visualização dos valores digitados
- [x] Botões de iteração com o usuário
- [x] Funcionalidade da tecla "Enter" para efetuar os cálculos e "Esc" para limpar a tela

# Link
A hospedagem foi feita utilizando o GitHub, que oferece serviço de hospedagem de sites.
- [URL do Site](https://epfolletto.github.io/calculadora/)

# Tecnologias
<div>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">  
<img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">
</div>

# Autor
Evandro Paulo Folletto
<div>
  <a href="https://github.com/epfolletto" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/evandrofolletto/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
  <a href="https://www.youtube.com/evandropaulofolletto" target="_blank"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" target="_blank"></a>
</div>
