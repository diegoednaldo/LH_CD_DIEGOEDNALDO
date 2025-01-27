# Projeto de Análise e Modelagem de Preços de Aluguéis Temporários em Nova York

Este projeto tem como objetivo realizar uma análise exploratória de dados e desenvolver um modelo preditivo para preços de aluguéis temporários na cidade de Nova York. O projeto foi desenvolvido utilizando o **Google Colab**, uma plataforma baseada em nuvem que permite a execução de código Python em notebooks interativos.

## Pré-requisitos

Para executar este projeto, você só precisa de:

- Uma **conta Google** para acessar o Google Colab.
- O arquivo de dados `teste_indicium_precificacao.csv` que será carregado no Google Colab.

## Passos para Executar o Projeto no Google Colab

### 1. Acesse o Google Colab

- Acesse o [Google Colab](https://colab.research.google.com/).
- Faça login com sua conta Google, se necessário.

### 2. Carregue o Notebook

- Se você já tem o arquivo `.ipynb` (notebook) salvo no Google Drive ou localmente, você pode carregá-lo diretamente no Colab:
  1. Clique em **"Arquivo"** no menu superior.
  2. Selecione **"Abrir notebook"**.
  3. Escolha a opção **"Upload"** para carregar o arquivo `.ipynb` do seu computador, ou **"Google Drive"** se o arquivo estiver salvo no Drive.

- Se você não tem o notebook, pode criar um novo e copiar o código do arquivo fornecido.

### 3. Carregue o Conjunto de Dados

- No Google Colab, você pode carregar o arquivo `teste_indicium_precificacao.csv` diretamente para a sessão atual:
  1. Clique no ícone de **"Arquivos"** no painel esquerdo.
  2. Clique em **"Fazer upload para o armazenamento da sessão"**.
  3. Selecione o arquivo `teste_indicium_precificacao.csv` do seu computador.

- O arquivo será carregado temporariamente para a sessão atual do Colab. Certifique-se de que o caminho para o arquivo no código esteja correto (geralmente, o Colab usa o caminho `/content/` para arquivos carregados).

### 4. Execute o Código

- O notebook está dividido em seções que correspondem às etapas do projeto:
  1. **Análise Exploratória de Dados**: Aqui, os dados são explorados, e gráficos e estatísticas descritivas são gerados.
  2. **Limpeza de Dados**: Identificação e remoção de outliers e valores nulos.
  3. **Modelagem Preditiva**: Construção e avaliação de modelos de regressão (Random Forest e Gradient Boosting).
  4. **Exemplo de Previsão**: Uso do modelo treinado para prever o preço de um novo apartamento.

- Execute cada célula do notebook sequencialmente clicando no botão **"Play"** ao lado de cada célula ou pressionando **Shift + Enter**.

### 5. Resultados

- Após a execução do código, você verá os resultados diretamente no notebook, incluindo gráficos, métricas de avaliação dos modelos (como RMSE) e previsões de preços.

## Estrutura do Projeto no Google Colab

- **Células de Código**: Cada etapa do projeto está dividida em células de código que podem ser executadas individualmente.
- **Células de Texto**: Explicações e comentários sobre o que está sendo feito em cada etapa.
- **Gráficos e Visualizações**: Gráficos interativos gerados com `seaborn` e `matplotlib`.
- **Modelos de Machine Learning**: Dois modelos de regressão são treinados e comparados (Random Forest e Gradient Boosting).

## Dicas para Usar o Google Colab

- **Armazenamento de Sessão**: Os arquivos carregados para o Colab são armazenados apenas durante a sessão atual. Se você fechar o navegador ou a sessão expirar, os arquivos serão perdidos. Para evitar isso, você pode salvar os arquivos no Google Drive e montar o Drive no Colab.
  
  Para montar o Google Drive:
  ```python
  from google.colab import drive
  drive.mount('/content/drive')
  ```
  Depois, você pode acessar os arquivos no Drive pelo caminho `/content/drive/MyDrive/`.

- **Salvar o Notebook**: Você pode salvar o notebook no Google Drive ou fazer o download do arquivo `.ipynb` para o seu computador.

## Conclusão

Este projeto oferece uma análise detalhada dos dados de aluguéis temporários em Nova York e propõe modelos preditivos para estimar o preço dos aluguéis.

Para qualquer dúvida ou sugestão, sinta-se à vontade para entrar em contato ou abrir uma issue no repositório.

---

**Nota**: Certifique-se de que o arquivo `teste_indicium_precificacao.csv` esteja carregado corretamente no Google Colab para que o código funcione sem erros.
