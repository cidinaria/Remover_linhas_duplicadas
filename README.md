#Remover_linhas_duplicadas

```python
import pandas as pd
```
##Carregar o arquivo CSV

```python
df = pd.read_csv('arquivo.csv')
```

##Remover linhas duplicadas, mantendo a primeira ocorrência

```python
df_sem_duplicatas = df.drop_duplicates()
```

##Salvar o arquivo sem duplicatas

```python
df_sem_duplicatas.to_csv('arquivo_ok.csv', index=False)
print("Linhas duplicadas removidas com sucesso!")
```
