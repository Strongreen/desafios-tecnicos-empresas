# desafios-tecnicos-empresas
Resolvi reunir vários desafios tecnicos aqui para ajudar vocês a se prepararem quando chegar nessa etapa

Vou replicar alguns enunciados para se basearem e quando for resolver o exercicio, lembra de fazer um fork e me manda mensagem, bora ajudar mais pessoas ;)

**1**

Crie uma aplicação, utilizando uma linguagem de programação de sua escolha, que gerencia
as reservas, confirmações e remoção de reservas de poltronas de um teatro.
O teatro possui 100 poltronas, divididas em 10 filas de 10 poltronas.
Essa aplicação deverá ter como funcionalidade:
 - Mostrar todos os lugares disponíveis.
 - Fazer uma reserva
 - Confirmar uma reserva
 - Retirar uma reserva (confirmada ou não confirmada)
 - Mostrar o mapa de lugares (Reservados, Confirmados e Livres)
 - Calcular o valor de arrecadação sendo que: Cada poltrona confirmada vale R$ 20,00
 - Mostrar o total de lugares reservados
 - Mostrar o total de lugares confirmados
 - Mostrar o total de lugares disponíveis
 
Utilize todos os recursos necessários para que a aplicação seja de fácil utilização para o
usuário.
* Utilize as siglas: L para Livre; C para Confirmado; e R para reservado)

_________________________________________________________________________________

**2**
Utilizando uma linguagem de programação de sua escolha, faça um algoritmo que dado um
número inteiro de 1 a 100, imprima na tela o desenho de um círculo preenchido por caracteres
se sua escolha onde o número inteiro será o raio de caracteres do círculo.
Por exemplo, dado o número inteiro 5, uma possibilidade de desenho é a seguinte:

http://prntscr.com/1xrzhyd

_________________________________________________________________________________

**3**

Utilizando algum framework de desenvolvimento web ou HTML, JavaScript (ou JQuery) e CSS
(ou algum framework css) crie uma aplicação de to-dos (afazeres).
A aplicação deve:
 - Ter 3 abas onde ficará as atividades: a fazer, em progresso e finalizado;
 - Ter um input de texto onde o usuário poderá inserir suas atividades;
 - Ter um botão para limpar todas as tarefas;
 - Ter um botão em cada tarefa para excluir;
 
**Funcionalidade:**
 - Ao inserir alguma atividade no input, ela deve ir automaticamente para a aba ‘a fazer’;
 - As atividades que estão na aba ‘a fazer’ deverá ter um botão que mova a atividade para a aba ‘em progresso’;
 - Por sua vez as atividades ques estão na aba ‘em progresso’ deverá ter um botão que mova para aba ‘finalizado’;

**Ah, e não esqueça de caprichar no design!**

Adicional:
Caso o usuário feche a página e abra novamente os dados inseridos anteriormente devem
estar presentes

_________________________________________________________________________________

**4**

Instruções gerais

 - Pode ser utilizada qualquer linguagem.
 - Utilizar somente bibliotecas padrão da linguagem escolhida.
 - Testes unitários são opcionais.
 - A interface do sistema construído deve ser do tipo console.
 - O código deve ser executável.
 
 O que deve ser enviado
 - Código construído.
 - Premissas assumidas.
 - Decisões de projeto.
 - Instruções para executar o sistema.

O problema
Senhor Eduardo é proprietário de um canil em Belo Horizonte, ele trabalha com diversas
raças, pequenas e grandes. Eduardo gosta que seus cães estejam sempre arrumados,
felizes e cheirosos.

No bairro do canil, para realizar o banho nos animais, existem três petshops: Meu Canino
Feliz, Vai Rex, e ChowChawgas. Cada um deles cobra preços diferentes para banho em
cães pequenos e grandes e o preço pode variar de acordo com o dia da semana.

 - Meu Canino Feliz: Está distante 2km do canil. Em dias de semana o banho para
cães pequenos custa R$20,00 e o banho em cães grandes custa R$40,00. Durante
os finais de semana o preço dos banhos é aumentado em 20%.

 - Vai Rex: Está localizado na mesma avenida do canil, a 1,7km. O preço do banho
para dias úteis em cães pequenos é R$15,00 e em cães grandes é R$50,00.
Durante os finais de semana o preço para cães pequenos é R$ 20,00 e para os
grandes é R$ 55,00.

 - ChowChawgas: Fica a 800m do canil. O preço do banho é o mesmo em todos os
dias da semana. Para cães pequenos custa R$30 e para cães grandes R$45,00.
Apesar de se importar muito com seus cãezinhos, Eduardo quer gastar o mínimo possível.
Desenvolva uma solução para encontrar o melhor petshop para levar os cães. O melhor
petshop será o que oferecer menores preços, em caso de empate o melhor é o mais
próximo do canil.

Entrada:
<data> <quantidade de cães pequenos> <quantidade cães grandes>
Exemplo: 03/08/2018 3 5
  
Saída:
Nome do melhor canil e preço total dos banhos

_________________________________________________________________________________
    
 **5** 
 
 Após uma reunião com a Diretoria, a equipe de Analistas da MMtools decidiu que
era necessário desenvolver uma nova funcionalidade para o sistema:
  
1. O usuário poderá escolher alguns produtos no site e adiciona-los ao carrinho
de compras.
2. Esse carrinho conterá o total de compras efetuadas;
3. As informações do carrinho NÃO deverão ser gravadas no banco de dados;
4. Deverá ter um acesso administrador para cadastrar os produtos, promoções
e editar usuários.
5. O que será gravado no banco de dados (as tabelas podem ter mais
informações se necessário):
  
**a. Cadastro de clientes com as informações:**
  
  
|Nome da coluna |Descrição |
|----------|:-------------:|
|ClienteId      |ID do cliente. (Obrigatório)|
|Nome           |Nome do cliente. (Obrigatório)|
|Email          |Email do cliente. (Obrigatório)|
|DataCadastro   |Data de cadastro do cliente no sistema (Obrigatório)|
|DataModificacao |Data em que os dados do cliente foram alterados.|
|Telefone       |Telefone do cliente. (Obrigatório)|
|Ativo          |Se o cliente está ativo ou inativo no sistema. (Obrigatório)|
|Cpf            |CPF do cliente.|
|DataNascimento |Data de nascimento do cliente.|
  
**b. Cadastro de produtos:**
  1. ProdutosID
  2. Descrição
  3. Preço de Venda
**c. Promoções de vendas:**
  1. Descrição da promoção
  2. Data de validade
  3. Produto
  4. Quantidade mínima
  5. Desconto
  
Ex: leve 3 pague 2, Acima de 5 20% desconto
  
**d. Histórico de compras**
 Observação importante:
  1. Para concluir a compra, o usuário precisa estar logado;
  2. Deve ser possível cadastrar um novo cliente sem estar logado no sistema.
  3. Somente um usuário do tipo administrador pode exercer o CRUD nas tabelas.
  
**Especificações básicas (Mínimo a ser feito):**
  1. O sistema deve ser desenvolvido utilizando o ASP.NET MVC 4.0 ou superior;
  2. O sistema deve ser desenvolvido em C#;
  3. Utilizar o EntityFramework;
  4. Utilizar o Bootstrap;
  5. Utilizar o Jquery;
  6. Deve ser possível pesquisar os clientes cadastrados na tela do administrador;
  7. Se necessário, os campos devem ser validados;
  8. O campo Telefone deve ter a seguinte formatação: (00) 0000-00000;
  9. O campo CPF deve ter seguinte formatação: 000.000.000-00;
  10.O código deve executar no Visual Studio 2015 ou superior;
  
**Especificações avançadas (Ponto extra para cada item abaixo):**
  1. Utilizar DDD;
  2. Utilizar TDD e/ou BDD;
  3. Autenticação do usuário e administrador via Token;
  4. Back-end do sistema desenvolvido somente com Web API;
  5. Front-end do sistema desenvolvido em Angular;
  
**Diferenciais:**
  1. Boas práticas de desenvolvimento (SOLID);
  2. Comentários;
  3. Documentação (Diagrama de classes, Casos de uso, etc.);

**  Entrega:**
   - Deverá ser enviado, um arquivo .zip ou .rar, o código do projeto e o script de criação do banco de dados.
 
 _________________________________________________________________________________
 
 **6**
 
 Vamos criar um site para visualização de dados de cotações de criptomoedas em tempo real?

Dadas as cotações de criptomoedas reportadas em tempo real através de uma API pública, você deve criar um projeto em React que irá exibir um ranking com estes dados (com informações de preço, variação, volume, entre outras). Podem ser implementados filtros e paginação para melhorar a experiência do usuário.

Além disso, deve permitir ao usuário navegar para uma página com informações específicas de uma determinada moeda. Aqui podem ser exibidas informações como o book de ofertas, histórico de trades, gráficos, entre outros. A API a ser consumida é a Poloniex Public API (https://docs.poloniex.com) (mais especificamente os comandos disponíveis na Public HTTP API Methods ou o canal websocket Ticker Data).

**Tecnologias avaliadas**

 - React.
 - Uma ferramenta de gerenciamento de estado (de preferência Redux Thunk)
 - Variedade de componentes React com diferentes complexidades
 - Webpack
 - JavaScript moderno
 - GIT (Avaliamos o histórico de commits)
 - Testes Unitários (De preferência Jest/Enzyme)

**Dados avaliados**
 
 _________________________________________________________________________________
 
 **7**
 
 
# Desafio - Back-End
 
Oi, candidato(a). Parabéns por ter chegado até essa fase do nosso processo! Isso
mostra que vemos potencial em seu perfil para se tornar um FERA na Dito :)
Nessa etapa, estamos lançando um desafio para saber como você lidaria com
situações que, para o nosso Desenvolvedor Back-End, serão bem comuns.
 
Algumas dicas:
 
 - Leia e releia os enunciados quantas vezes for preciso para entender o
problema. Pense em todos os aspectos que estão envolvidos nas situações e
procure responder da maneira mais completa possível, para que possamos
entender como você organiza e apresenta suas ideias;
 
 - Nós sabemos que você não tem tanto contexto sobre a plataforma da Dito,
por isso colocamos todas as informações de que você precisa no enunciado ;)
Preparado(a)? Vamos lá!
 
A Dito coleta bilhões de eventos de comportamento on/offline e um dos desafios
diários é gerar valor para os usuários através de informações consistentes e
acessíveis.
 
Esse desafio é composto por 2 partes: um Serviço de Autocomplete e um
problema de Manipulação de Dados.
 
**1 - Serviço de Autocomplete**
O serviço deve conter uma API Coletora de dados e o mecanismo de Autocomplete propriamente dito

 - Chamada de API
 - Criatividade
 - Boas práticas
 - Documentação (Preferência: README.md no GIT)

**Orientações**

 - A nossa avaliação é subjetiva e por isto te damos a liberdade de escolher a forma como você quer representar os dados, lembrando a criatividade é um dado avaliado e pode ser eliminatória. Avaliamos que o tempo médio para terminar o foco principal desta tarefa é de cerca de 1 semana.
 - Será avaliado o que for entregue. Assim, é importante documentar as dores e dificuldades.
 - Encontrando qualquer dúvida, você poderá entrar em contato conosco via email.

**Tempo de Execução**

5 dias ( dias corridos)

 _________________________________________________________________________________
 
 **8**
 
 
 # API Coletora
 
Você deverá construir uma API para coletar e armazenar os dados. Esta API deverá
receber informações de navegação dos usuários em um site. Um exemplo seria:
 ```
    {
    "event": "buy",
    "timestamp": "2016-09-22T13:57:31.2311892-04:00"
    }
 ```
**Autocomplete**
 
O mecanismo de autocomplete deve ser implementado e disponibilizado através de
uma API, contendo um campo de busca que deverá completar o nome dos eventos
a partir da segunda letra que o usuário digitar.
 
**2 - Manipulação de Dados**
O objetivo é criar uma timeline de compras a partir dos eventos disponíveis neste
endpoint:[events.json].
 
Um evento representa um comportamento de uma pessoa, seja no mundo online
ou offline. Quando uma pessoa faz uma compra, um evento comprou é gerado
contendo o total de receita gerada e o nome da loja. Para cada produto dessa
compra é gerado um evento comprou-produto, contendo o nome e preço do
produto.
 
Você deve implementar uma função, em qualquer linguagem de programação, que
consuma esse endpoint e agrupe as compras pelo campo transaction_id. Cada
item da timeline deve representar uma compra em uma determinada loja e deve
conter uma lista com os produtos comprados.
 
 A timeline deve ser ordenada pelo campo timestamp na ordem decrescente.
A resposta esperada dessa função é a seguinte:
 
{
   "timeline": [
     {
      "timestamp": "2016-10-02T11:37:31.2300892-03:00",
      "revenue": 120.0,
      "transaction_id": "3409340",
      "store_name": "BH Shopping",
   "products": [
       {
       "name": "Tenis Preto",
       "price": 120
       }
     ]
   },
   {
   "timestamp": "2016-09-22T13:57:31.2311892-03:00",
   "revenue": 250.0,
   "transaction_id": "3029384",
   "store_name": "Patio Savassi",
   "products": [
         {
         "name": "Camisa Azul",
         "price": 100
         },
         {
         "name": "Calça Rosa",
         "price": 150
         }
      ]
   }
 ]
}
 
 
** Premissas**
 
 - A solução deve ser escalável, preparada para receber um grande volume de
requisições;
 
 - As APIs do serviço de autocomplete devem responder num tempo
satisfatório, que não comprometa a experiência dos usuários, mesmo com
um grande volume de dados;
 
 - O desenvolvimento pode ser feito utilizando qualquer linguagem de
programação e qualquer sistema de banco de dados, cabendo ao
desenvolvedor escolher o que for melhor para a situação, mas será
considerado como um diferencial o uso de um banco de dados local e de
containers.
 
 - Serão avaliados a arquitetura, os padrões utilizados para o desenvolvimento
e a entrega no prazo
