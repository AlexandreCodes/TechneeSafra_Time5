# Previsão de Saúde Financeira de clientes - Technee Safra

Segmentação de clientes baseada no balanço de entrada e saída da conta

É possível classificar o comportamento nas seguintes categorias:


- Risco iminente de **inadimplência**
- Risco de **inadimplência** 2
- Risco de** inadimplência** 1
- Neutro
- Possível** investidor**
- **Investidor**

![alt text](https://i.ibb.co/4mpS5vH/img.png)

#  Pré-requisitos
- Conexão ao banco de dados MySQL Local criado para este projeto (verificar config.ini)

# Descrição técnica

- Desenvolvido em Python 3.7
- Sklearn API para treino do K-Means
- 6 Clusters (Baseado no Elbow Method)
- PyInstaller 4.0 para geração de .exe standalone
- MySQL 8

Informações completas do treino do modelo e dependências disponíveis no jupyter notebook '00-Criacao_Dataset_Modelagem_KMeans.ipynb' e no arquivo 'requirements.txt' respectivamente.

# Como determinar o grupo de um cliente

- Editar o arquivo config.ini com os dados de conexão do banco de dados e dicionário de clusters
- Executar o arquivo "model.exe" 
- No banco de dados, há uma tabela chamada "modelo" e após finalizar a execução, o segmento do cliente estará descrito nessa tabela.

# Disclaimer

Isso não é um produto oficial do banco Safra

A previsão de Saúde financeira de clientes é uma projeto utilizando um dataset financeiro sintético para treino, fruto de um hackathon promovido pelo banco safra para o processo seletivo de Technee.

## Time 5

- Alexandre França
- Guilhemo Valdez
- Luiz Guilherme Motta
- Nicolas Sathler de Araujo
- Rodrigo Coimbra