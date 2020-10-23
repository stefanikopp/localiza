# Projeto Localiza 
<b>Trabalho 1</b> <br>
<b>Disciplina:</b> Projeto e Arquitetura de Software <br>
<b>Professora:</b> Ana Terra Bacelos <br>
<b>Time:</b> Camila Borba, Jessica Manoel, Stefani Kopp, Victoria Azevedo

# Introdução
Neste documento estão registradas as partes significativas das escolhas de arquitetura do projeto para um sistema de registro de pedidos dos usuários nos mais diversos e-commerces, assim sendo um local único para acompanhamento e histórico de compras.

# Requisitos e Restrições Arquiteturais
Softwares Utilizados <br>
     - 
Linguagem escolhida <br>
     -

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
     
<h2>Diagrama de Caso de Uso</h2> 

![Alt Text](https://github.com/stefanikopp/localiza/blob/main/diagrama_caso_de_uso.JPG)

# Visão Lógica

# Visão de Implantação

# Atributo de Qualidade

Ecolhemos como atributo de qualidade manutenibilidade, a estruturação do projeto foi feito pensando em seguir o mais fiel possivel a arquitetura e padrões geralmente
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
