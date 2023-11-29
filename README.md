<h1 align="center">Sistema de Zoológico</h1>

## **Sumário:**<a name="sumario"></a>
- <a href="#1">Introdução</a>
- <a href="#2">Como Instalar</a>
- <a href="#3">Classes</a>
- <a href="#4">Pessoas Envolvidas</a>

## Introdução <a name="1"></a><a href="#sumario">:arrow_double_up:</a>
<p align="justify">
Bem-vindo ao nosso projeto, um sistema projetado para simplificar o controle de animais em zoológicos. Nosso software oferece uma maneira fácil e eficiente de gerenciar a adição e remoção de animais, garantindo um processo organizado e transparente. Ao utiliza-lo, você terá uma visão completa das entradas e saídas de animais, facilitando a gestão do acervo do zoológico e garantindo o cuidado contínuo e responsável de todas as espécies.
</p>

## Como Instalar <a name="2"></a><a href="#sumario">:arrow_double_up:</a>
### 1. Plataforma
1. Você pode usar vários IDE (ambientes de desenvolvimento de software) para executar o projeto, mas o mais fácil de fazer é com o [IDE Intellij IDEA](https://www.jetbrains.com/idea/), visto que não são necessários plugins ou coisas do gênero para fazer com que o projeto compile, a escolha do IDE é de sua preferência.
2. Também é necessário que você tenha um programa para descompactar arquivos (WinRar, 7Zip), visto que o projeto será baixado como um .zip e você não terá acesso a ele sem um programa para descompacta-lo.
3. Deve baixar o projeto para sua máquina.

### 2. Executando o Projeto
Para executar o projeto, deve seguir os seguintes passos:
1. Entre no IDE Intellij IDEA, e dentro dele, abra a pasta do projeto;
2. Estando com o projeto aberto, abra a pasta `main`, entre no arquivo `JanelaZoologico.java` e o execute (Obs: Por conta do tamanho do arquivo, talvez demore ao executa-lo).

## Classes <a name="3"></a><a href="#sumario">:arrow_double_up:</a>
- **animals**\
  Está é classe dos animais, com a classe `animals` sendo a classe abstrata e genérica que define as coisas que um animal **DEVE** ter.
    - Como nome, especie e tipo de dieta.
  
  Essa classe também lida com a estrutura dos animais.
    - getters e setters para nomes e tipos de dieta e pelagem, por exemplo.
  
  A sub classe anfibio, anfibio venenoso, ave, mamífero, reptil e reptil venenoso são herdeiras da classe animal, isso é, elas herdam as características necessárias para serem animais.
    - Como nome, especie e tipo de dieta.
      
  Mas também tem características próprias, como o tipo de pelagem dos mamíferos, o veneno dos répteis e anfíbios, a envergadura das asas das aves, etc.
- **enums**\
  Essa classe foi feita basicamente para padronizar as dietas dos animais, que são: carnívoro, herbívoro ou onívoro.
- **main**\
  O arquivo `JanelaZoologico.java` tem o pacote `main`, ela age como uma main padrão de um projeto, é aqui que ocorre a entrada dos valores no programa.
- **zoo**\
  A classe `Zoologico.java` lida com toda a lógica de programação da parte estrutural do zoológico. Ou seja, ela lida com coisas como:
  - Inicializar a lista dos animais;
  - Listar os animais no console;
  - Adicionar animal a lista;
  - Remover um animal da lista;
  - Criar um animal com base nas entradas do usuário;
  - Obter o tipo de dieta do animal com base na escolha do usuário;
  - Remover o animal da lista com base no nome fornecido;
  - Verificar a existência do animal na lista;
  - Listar os animais por nome em ordem alfabética;
  - Adicionar as informações à interface gráfica ao invés de imprimi-las no console.

## Pessoas Envolvidas <a name="4"></a><a href="#sumario">:arrow_double_up:</a>
- [Andressa Monteiro](https://github.com/AndressaUwU) 
- [Gabriel Rocha](https://github.com/CSeisOssos)
- [Maria Eduarda](https://github.com/MariaXubilu)
