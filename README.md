# Análise Geoespacial dos Bairros de Natal/RN

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![Geopandas](https://img.shields.io/badge/Geopandas-green?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-orange?style=for-the-badge)

## 🗺️ Sobre o Projeto

Este projeto realiza uma análise exploratória de dados geoespaciais (AED) dos limites dos bairros do município de Natal, capital do Rio Grande do Norte, Brasil.

O objetivo principal é carregar, analisar e visualizar os dados contidos em um arquivo shapefile (`.shp`), classificando os bairros por Região Administrativa (Norte, Sul, Leste e Oeste) e gerando um mapa coroplético detalhado com os nomes de cada bairro.

## 📊 Prévia do Resultado

O resultado final é um mapa que exibe claramente as divisões geográficas, permitindo uma fácil identificação dos bairros e de sua respectiva zona administrativa.

*(Dica: Tire um print do mapa gerado no Colab, salve como `mapa_natal_bairros.png` e adicione ao seu repositório para que a imagem apareça aqui.)*

![Prévia do Mapa](Mapa_Natal_bairros.png)

## 🛠️ Tecnologias Utilizadas

* **Python:** Linguagem principal para a análise.
* **Geopandas:** Biblioteca essencial para a manipulação e análise de dados geoespaciais.
* **Pandas:** Utilizada pelo Geopandas para a estruturação dos dados de atributos.
* **Matplotlib:** Biblioteca para a plotagem e customização do mapa.
* **Google Colab:** Ambiente de notebook utilizado para a execução do código.

## 🚀 Como Executar o Projeto

Você pode replicar esta análise seguindo os passos abaixo:

1.  **Clone ou baixe este repositório:**
    ```sh
    git clone [https://github.com/jeppa1/geodata-natal.git](https://github.com/jeppa1/geodata-natal.git)
    ```

2.  **Prepare o Ambiente no Google Colab:**
    * Acesse [colab.research.google.com](https://colab.research.google.com) e crie um novo notebook.
    * No painel à esquerda (ícone de pasta), faça o upload de todos os arquivos do shapefile (`Limite_Bairros.shp`, `.shx`, `.dbf`, etc.) para o armazenamento da sessão.

3.  **Instale as Dependências:**
    Execute a seguinte célula de código para instalar o `geopandas`:
    ```python
    !pip install geopandas
    ```

4.  **Execute o Script:**
    Copie o conteúdo do arquivo `.ipynb` deste repositório para uma nova célula no seu notebook e execute-a para realizar a análise e gerar o mapa.

## 🔬 Metodologia Aplicada

A análise seguiu uma metodologia estruturada de 5 passos, conforme o escopo original:

1.  **Diagnóstico dos Dados e Formulação de Hipóteses:** Carga e inspeção inicial da estrutura do shapefile.
2.  **Pré-processamento e Limpeza:** Verificação de dados nulos, consistência e sistema de coordenadas (CRS).
3.  **Análise Descritiva e Estatística:** Contagem e agrupamento dos bairros por Região Administrativa.
4.  **Visualização de Dados e Geração de Insights:** Criação do mapa coroplético para visualização espacial.
5.  **Síntese Executiva e Recomendações:** Resumo dos achados e sugestão de próximos passos.

## 📂 Estrutura do Repositório

```
.
├── data/                  # Pasta contendo os arquivos do shapefile
│   ├── Limite_Bairros.shp
│   ├── Limite_Bairros.shx
│   └── ... (demais arquivos)
├── analise_bairros_natal.ipynb  # Notebook principal com o código
└── README.md                    # Documentação do projeto
```

## ✒️ Autor

**Jadson Chagas**

* LinkedIn: [https://linkedin.com/in/seu-linkedin](https://linkedin.com/in/jadson-chagas)
* GitHub: [https://github.com/seu-usuario](https://github.com/jeppa1)
