# Projeto Localiza 
<b>Trabalho 1</b> <br>
<b>Disciplina:</b> Projeto e Arquitetura de Software <br>
<b>Professora:</b> Ana Terra Bacelos <br>
<b>Time:</b> Camila Borba, Jessica Manoel, Stefani Kopp, Victoria Azevedo

# Introdução
Neste documento estão registradas as partes significativas das escolhas de arquitetura do projeto para um sistema de registro de pedidos dos usuários nos mais diversos e-commerces, assim sendo um local único para acompanhamento e histórico de compras.

O padrão de arquitetura de software escolhido para o projeto Localiza é o MVC (Model-View-Controller/Modelo-Visão-Controle), em que a aplicação é separada em camadas de diferentes níveis, cada camada tem uma tarefa distinta dentro do software.

A camada de Visão é relacionada ao visual da aplicação, ou seja, as telas que serão exibidas para o usuário. Nessa camada apenas os recursos visuais devem ser implementados, como janelas, botões e mensagens. 

Já a camada de Controle atua como intermediária entre as regras de negócio (camada Modelo) e a Visão, realizando o processamento de dados informados pelo usuário e repassando-os para as outras camadas. 

E por fim, temos a camada de Modelo, que consiste na essência das regras de negócio, envolvendo as classes do sistema e o acesso aos dados. 

<h3> Representação MVC </h3>

![Alt Text](https://github.com/stefanikopp/localiza/blob/main/representacao_MVC.jpeg)


# Requisitos e Restrições Arquiteturais
<h4>Softwares Utilizados</h4>

•	Node.js; <br>
•	Gerenciador de dependências Yarn;<br>
•	Software de gerenciamento de Banco de Dados DataGrip;<br>
•	IDE VS Code.


# Visão de Caso de Uso - User Stories

<b>US01 - Cadastrar Ecommerce</b><br>
     Eu como usuário do sistema <br>
     Gostaria de poder cadastrar um ecommercer<br>
     Para que eu eu possa acompanhar meu pedido no mesmo.
     
<b>US02 - Importar pedidos</b><br>
     Eu como usuário do sistema <br>
     Gostaria de poder importar meu pedidos de um ecemmerce especifico <br>
     Para ter um controle unico de pedidos.
     
<b>US03 - Filtrar pedido por ecommerce</b><br>
     Eu como usuário do sistema <br>
     Gostaria de poder filtrar meu pedidos por ecommerce<br>
     Para que eu consiga controlar os pedidos feito em um determinado ecommerce.
     
<b>US04 - Gerar relatório por ecommerce</b><br>
     Eu como usuário do sistema<br>
     Gostaria de poder gerar um relatório por ecommerce<br>
     Para guardar um documento com o meu histórico de compra.
     
<b>US05 - Gerar relatório por status</b><br>
     Eu como usuário do sistema<br>
     Gostaria de poder gerar um relatório por status de pedido<br>
     Para pode controlar os pedidos já entregue.
     
# Diagrama de Caso de Uso

![Alt Text](https://github.com/stefanikopp/localiza/blob/main/diagrama_caso_de_uso.JPG)

# Visão Lógica

![classe](https://github.com/stefanikopp/localiza/blob/main/dia-classe.jpeg)


# Visão de Implantação
Como os componentes de software são distribuidos na infraestrutra de hardware, ilustração através do diagrama de deployment das relações físicas entre componentes de software e hardware no sistema.

<b>Diagrama de Deployment<b/>

![deploy](https://github.com/stefanikopp/localiza/blob/main/diagrama_deployment.JPG)

<b>Diagrama de Componentes<b/>
![comp](https://github.com/stefanikopp/localiza/blob/main/diagrama-comp.jpeg)

# Atributo de Qualidade

Ecolhemos como atributo de qualidade <b>manutenibilidade</b>, a estruturação do projeto foi feito pensando em seguir o mais fiel possivel a arquitetura e padrões geralmente
utilizadas para que qualquer desenvolvedor que tenha um conhecimento sobre as mesmas consiga implementar novas features.

# Configurações do Projeto

<b>Front-End</b><br>
```bash
https://github.com/stefanikopp/localiza-frontend
```

<b>Back-End</b><br>
```bash
https://github.com/stefanikopp/back-end-locoliza
```

<b>Banco de Dados</b><br>
```bash
MySQL
nome: pedidos_ecommerce
host: localhost
user: root
password: 12345678
```
