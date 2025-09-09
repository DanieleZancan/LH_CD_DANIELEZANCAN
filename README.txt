📘 README – Análise de Filmes

📌 Sobre o projeto:

Este projeto faz parte de um desafio técnico do Programa Lighthouse.

O objetivo é:
-Realizar uma análise exploratória (EDA) da base de dados de filmes do IMDB.
-Responder perguntas sobre os fatores que influenciam as notas e bilheteria.
-Construir um modelo preditivo simples para prever a nota do IMDB.

🛠️ Tecnologias utilizadas:

-Python 3.9+
-Pandas → manipulação de dados
-Matplotlib / Seaborn → visualização gráfica
-Scikit-learn → modelagem preditiva e métricas
-Joblib → salvar e carregar o modelo treinado

📂 Estrutura do projeto:

📦 LH_CD_DANIELEZANCAN
 ┣ 📂 data
 ┃ ┗ desafio_indicium_imdb.csv   # Base de dados
 ┣ 📂 notebooks
 ┃ ┗ analise_filmes.ipynb        # Notebook com a análise e modelo
 ┃ ┗ modelo_imdb.pkl             # Modelo salvo (gerado pelo notebook)
 ┃ README.txt                    # Este arquivo 
 ┗ requiriments.txt              # Tecnologias utilizadas 

🚀 Como instalar e executar:

1. Clonar o repositório
git clone https://github.com/DanieleZancan/LH_CD_DANIELEZANCAN.git
cd LH_CD_DANIELEZANCAN

2. Criar ambiente virtual (opcional, mas recomendado)
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

3. Instalar dependências
pip install -r requirements.txt

4. Abrir no VSCode com Jupyter

-Instale a extensão Jupyter no VSCode.
-Abra o arquivo notebooks/analise_filmes.ipynb.
-Selecione o interpretador Python correto.
-Execute célula por célula (Shift+Enter) ou clique em Run All.

📊 Resultados obtidos:

-Filmes com mais votos e boa avaliação da crítica (Meta_score) tendem a ter notas mais altas no IMDB.
-O faturamento (Gross) não tem forte correlação com a nota.
-O modelo de Regressão Linear conseguiu prever notas com desempenho razoável (métricas R² e RMSE estão no notebook).
-A nota prevista para The Shawshank Redemption ficou próxima da nota real (9.2).
