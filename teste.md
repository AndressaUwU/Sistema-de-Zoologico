<h1 align="center">Sistema de Hotel</h1>

## **Sumário:**<a name="sumario"></a>
- <a href="#1">Introdução</a>
- <a href="#2">Como Instalar</a>
- <a href="#3">Funções</a>
- <a href="#4">Pessoas Envolvidas</a>

## Introdução <a name="1"></a><a href="#sumario">:arrow_double_up:</a>
<p align="justify">
Bem-vindo ao nosso projeto...
</p>

## Como Instalar <a name="2"></a><a href="#sumario">:arrow_double_up:</a>
### 1. Plataforma
1. Você pode usar...

### 2. Executando o Projeto
Para executar o projeto...

## Funções <a name="3"></a><a href="#sumario">:arrow_double_up:</a>
- **hotel.h**\
Definição da estrutura para uma reserva.\
Constante para o número máximo de quartos.
  - Função para inicializar o array de reservas;\
Esta função recebe um array de reservas e o número máximo de quartos.\
Ela inicializa cada reserva com valores padrão.

  - Função para fazer uma reserva;\
Esta função permite ao usuário fazer uma reserva para um quarto específico.\
Ela verifica se o quarto está livre, coleta informações do hóspede e atualiza o estado da reserva.

   - Função para realizar o check-in;\
Esta função permite ao usuário realizar o check-in para um quarto ocupado.

   - Função para realizar o check-out;\
Esta função permite ao usuário realizar o check-out para um quarto ocupado.\
Ela libera o quarto e atualiza o total de reservas.

   - Função para visualizar reservas;\
Esta função exibe informações sobre os quartos reservados.\
Se nenhum quarto estiver reservado, uma mensagem apropriada é exibida.

- **hotel.c**\
Inicializa o array de reservas, configurando cada quarto como livre e sem ocupante.\
Essa função evita problemas ao garantir que todos os quartos estejam prontos para receber reservas.

  - função..\ 
Realiza uma reserva em um quarto específico, solicitando informações do hóspede.\
Esta função fornece uma maneira de reservar um quarto e manter o controle de ocupação.\
Essa função é a principal função do programa, ela é basicamente como a caneta que escreve quais quartos serão reservados, por quem
e por quantos dias, isso funciona alocando um espaço na memoria, se ele for 1, o quarto está reservado, se for 0, está livre.

  - função..\ 
Realiza o check-in em um quarto específico, exibindo informações do hóspede se o quarto estiver ocupado.\
A função permite verificar quem está hospedado em um quarto antes de realizar o check-in, proporcionando uma visão rápida do estado do quarto, a função não especifica quantos dias a pessoa vai estar no quarto, apenas diz se ele está ocupado e se sim, quem o está ocupando.

  - função.\  
Realiza o check-out de um quarto específico, liberando o quarto se estiver ocupado.\
Esta função permite desocupar um quarto, garantindo que ele esteja pronto para novas reservas.\
Esta função basicamente reescreve o quarto selecionado de 1 para 0 no espaço de memória que foi alocado.

  - função.\ 
Exibe informações sobre os quartos reservados, indicando ocupante e tempo de reserva.\
A função fornece uma visão geral dos quartos ocupados, facilitando o acompanhamento dos hóspedes por parte da equipe do hotel.\
É uma das funções que mais importa, e a que mais apresentou erros na hora de testar o programa.\

## Pessoas Envolvidas <a name="4"></a><a href="#sumario">:arrow_double_up:</a>
- [Maria Eduarda](https://github.com/MariaXubilu)
