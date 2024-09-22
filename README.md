# Bootcamp-Engenharia-de-Dados__Fernando-Amaral

 Bootcamp realizado, no qual tive o primeiro contato com ferramentas como Airflow, Dbt e pude aprender na prática como contruir todo um fluxo desde a extração dos dados, tratamento e carregamento no Data Warehouse. Nesse Bootcamp foram utilizados ferramentas e linguagens como: SQL, Python, Snowflake, Airflow, DBT e Power BI. Foi utilizado nesse processo o EC2 da AWS e Docker para a implementação do ambiente do Airflow.


<h1 align="center"> Projeto: </h1>
<div align="center">
<img src="https://github.com/user-attachments/assets/8cd8406e-3a5d-4ffb-a7f8-3df5026c6861" width="900px" />
</div>
O projeto se trata de uma análise de vendas de uma concessionária fictícia "Nova Drive". Como podemos ver na imagem acima, os dados foram extraídos Postgre através do Airflow para o Snowflake, numa camada _RAW (sem tratamento). Após isso, foi utilizado o DBT para realizar o tratamento desses dados e novamente adicionado no Snowflake numa camada Analítica, para que os dados possam ser utilizados no Power BI.

<h2 align="center"> Imagens com as etapas do projeto: </h2>

<h3 align="center"> Airflow </h3>
<div align="center">
<img src="https://github.com/user-attachments/assets/18d0a8b2-0a93-4937-8f9b-7c28c0cda781" width="700px" />
</div>

<h3 align="center"> Snowflake </h3>
<div align="center">
<img src="https://github.com/user-attachments/assets/f88f4353-9e78-4dd7-87d1-df641e5223c7" width="700px" />
</div>

<h3 align="center"> Dbt </h3>
<div align="center">
<img src="https://github.com/user-attachments/assets/c665189d-f4b3-4e61-9609-9bd20ce92b5b" width="700px" />
</div>

<h3 align="center"> Dbt Lineage </h3>
<div align="center">
<img src="https://github.com/user-attachments/assets/eb5fa6b1-4bf5-499a-82c3-167f3d6b95dc" width="700px" />
</div>

<h3 align="center"> Resultado Final: </h3>
<div align="center">
<img src="https://github.com/user-attachments/assets/a1d022e8-6914-46ac-8ce6-55769f679f38" width="700px" />
</div>


## Linguagens, Ferramentas e Tecnologias utilizadas no processo:
#### -SQL
#### -Python
#### -Postgre
#### -AWS (EC2)
#### -Docker
#### -Snowflake
#### -Airflow
#### -DBT
#### -Power BI
