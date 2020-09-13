# Previs�o de Sa�de Financeira de clientes - Technee Safra

Segmenta��o de clientes baseada no balan�o de entrada e sa�da da conta

� poss�vel classificar o comportamento nas seguintes categorias:


- Risco iminente de **inadimpl�ncia**
- Risco de **inadimpl�ncia** 2
- Risco de** inadimpl�ncia** 1
- Neutro
- Poss�vel** investidor**
- **Investidor**

![alt text](https://i.ibb.co/4mpS5vH/img.png)

#  Pr�-requisitos
- Conex�o ao banco de dados MySQL Local criado para este projeto (verificar config.ini)

# Descri��o t�cnica

- Desenvolvido em Python 3.7
- Sklearn API para treino do K-Means
- 6 Clusters (Baseado no Elbow Method)
- PyInstaller 4.0 para gera��o de .exe standalone
- MySQL 8

Informa��es completas do treino do modelo e depend�ncias dispon�veis no jupyter notebook '00-Criacao_Dataset_Modelagem_KMeans.ipynb' e no arquivo 'requirements.txt' respectivamente.

# Como determinar o grupo de um cliente

- Editar o arquivo config.ini com os dados de conex�o do banco de dados e dicion�rio de clusters
- Executar o arquivo "model.exe" 
- No banco de dados, h� uma tabela chamada "modelo" e ap�s finalizar a execu��o, o segmento do cliente estar� descrito nessa tabela.

# Disclaimer

Isso n�o � um produto oficial do banco Safra

A previs�o de Sa�de financeira de clientes � uma projeto utilizando um dataset financeiro sint�tico para treino, fruto de um hackathon promovido pelo banco safra para o processo seletivo de Technee.

## Time 5

- Alexandre Fran�a
- Guilhemo Valdez
- Luiz Guilherme Motta
- Nicolas Sathler de Araujo
- Rodrigo Coimbra