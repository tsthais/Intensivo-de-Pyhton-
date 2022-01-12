#

<div>
  <h1 align="center"> Automação de Sistemas e Processos com Python ☎🔍📊</h1>
</div>

#

<h3>➡ Observação sobre o projeto </h3>

Visualização de dados é a minha parte favorita da análise de dados, eu fiquei muito animada com a aula oferecida pela Hashtag Programação. Tanto que as análises abaixo e os gráficos que seguem foram elaborados por mim. No notebook, em linguagem Python, existe um carrossel de gráficos que foi ensinado na aula. Eu entendi esse carrossel como um ponto de partida e pesquisei formas de como elaborar melhor estes gráficos.

#

<h3>➡ Desafio </h3>

Você trabalha em uma empresa de telecom e tem clientes de vários serviços diferentes, entre os principais: internet e telefone.

O problema é que, analisando o histórico dos clientes dos últimos anos, você percebeu que a empresa está com Churn de mais de 26% dos clientes.

Isso representa uma perda de milhões para a empresa.

O que a empresa precisa fazer para resolver isso?

Base de Dados: https://drive.google.com/drive/folders/1T7D0BlWkNuy_MDpUHuBG44kT80EmRYIs?usp=sharing <br>
Link Original do Kaggle: https://www.kaggle.com/radmirzosimov/telecom-users-dataset

#

<h3>➡ Passos que foram utilizados para resolver o desafio: </h3>

1. Importar a base de dados;


2. Visualizar a base de dados; 


3. Tratamento de dados;


4. Análise inicial (para confirmar as hipóteses);


5. Análise detalhada dos clientes.

# 

<h3>➡ Resultados </h3>

A hipótese levantada de que a pelo menos 26% dos clientes da empresa de telefonia cancelavam seus serviços foi confirmada.

<p align="center">
  <img src="https://github.com/tsthais/Intensivo-de-Python-/blob/main/Analise_dados/newplot.png" />
</p>

Para entender quais tipos de clientes cancelam mais seus serviços foi feita uma análise nas variáveis que apresentavam uma maior taxa de cancelamento. A primeira variável analisada foi tipo de contrato, a partir dela foi possível identificar que clientes com contratos mensais cancelam mais os serviços contratados. 

<p align="center">
  <img src="https://github.com/tsthais/Intensivo-de-Python-/blob/main/Analise_dados/newplot%20(1).png" />
</p>

Outra variável que mostrou diferença significativa entre suas diferentes possibilidade foi a de depedência. Através do gráfico abaixo é possível verificar que clientes que não tem dependentes, ou seja, que não pacote familiar, cancelam mais do que os tem. 

<p align="center">
  <img src="https://github.com/tsthais/Intensivo-de-Python-/blob/main/Analise_dados/newplot%20(2).png" />
</p>


Além disso, outro dado importante foi de que clientes que estão nos primeiros meses de contrato acabam cancelando mais dos que tem mais tempo na empresa. Essa informação foi constatada através da análise da variável tempo do cliente na empresa.

<p align="center">
  <img src="https://github.com/tsthais/Intensivo-de-Python-/blob/main/Analise_dados/newplot%20(3).png" />
</p>

Outra importante análise foi de que os clientes que assinam o serviço de internet de fibra cancelam mais do que os clientes que não tem pacotes de internet ou dos que tem o serviço DSL.

<p align="center">
  <img src="https://github.com/tsthais/Intensivo-de-Python-/blob/main/Analise_dados/newplot%20(4).png" />
</p>

E por último foi visto que as pessoas que pagam por boletos eltrônicos também tendem a cancelar mais os produtos contratados. 

<p align="center">
  <img src="https://github.com/tsthais/Intensivo-de-Python-/blob/main/Analise_dados/newplot%20(5).png" />
</p>

# 

<h3>➡ Conclusões </h3>

- Clientes com contrato mensal tem MUITO mais chance de cancelar:
    - Pode- se fazer promoções para o cliente ir para o contrato anual.
    
- Famílias maiores tendem a cancelar menos do que famílias menores:
    - Pode- se fazer promoções pra pessoa pegar uma linha adicional de telefone.
    
- Clientes que tem menos tempo na empresa tem maior número de cancelamento:
    - A primeira experiência do cliente na operadora pode ser ruim;
    - Talvez a captação de clientes tá trazendo clientes desqualificados;
    - Ideia: a gente pode criar incentivo pro cara ficar mais tempo como cliente.
    
- Tem alguma coisa no nosso serviço de Fibra que tá fazendo os clientes cancelarem:
    - Investigar qual é o problema nesse tipo de serviço;
    - Aplicar mudanças para que melhore.
    
- Clientes que pagam através de boleo eletrônico tem MUITO mais chance de cancelar
     -  Então pode-se fazer alguma ação para eles irem para as outras formas de pagamento;
     -  Investigar por que isso acontece.


